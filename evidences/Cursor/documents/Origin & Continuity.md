# Origin & Continuity: Cursor's Git Infrastructure

- **Source:** https://www.theregister.com/devops/2026/08/23/how-cursor-beat-gits-scalability-shortcomings/5291421
- **Date:** August 23, 2026
- **Author:** SuperHero2010 Investigative Unit (Analysis)

---

## 1. Overview

Cursor has built its own Git-based repository service called **Origin**, powered by an internal engine named **Continuity**. The system uses Amazon S3 object storage instead of traditional distributed Git replicas to handle scalability challenges. The approach was detailed by Cursor principal systems engineer Vicent Martí.

---

## 2. The Problem

| Challenge | Description |
|-----------|-------------|
| **Git's DAG traversal** | Git must walk the entire directed acyclic graph to fulfill requests, which is slow at scale |
| **GitHub's Spokes** | Relies on at least 3 tightly synchronized NVMe replicas: more replicas = longer sync times |
| **Agents make it worse** | Agents create vast numbers of small, throwaway repositories |
| **400M+ repositories** | GitHub-scale is hard to maintain |

---

## 3. Cursor's Solution: Origin + Continuity

| Component | Function |
|-----------|----------|
| **Origin** | Cursor's Git repository service |
| **Continuity** | Internal engine powering Origin |
| **S3 Object Storage** | Source of truth, stores write-ahead logs (WAL) as immutable objects |
| **Local NVMe** | Fast "reference" copy for latency-sensitive operations |

### Architecture:

```
1. Push → S3 (WAL) + Local NVMe (reference copy)
2. Other replicas download changes as needed
3. DAG traversal happens locally on NVMe, not over network
4. Source of truth is always the WAL, not the local copy
```

---

## 4. Key Quotes

> *"Agents have fundamentally changed the way we work with software... More code, more PRs, more CI runs."*
> — Vicent Martí, Cursor

> *"With the only requirement of having to synchronize the reference transaction with a single local repository instead of a quorum of replicas, we have a system that can ingest pushes as fast as our disk allows."*

> *"Where does every repository live? The answer is 'anywhere'. It doesn't matter! We treat repositories like a warm cache on disk, but the source of truth is always the write-ahead log."*

---

## 5. What This Reveals About Cursor

| Observation | Implication |
|-------------|-------------|
| **Cursor is investing heavily in infrastructure** | They are building for scale: not just an editor, but a platform |
| **Origin is tied to paid plans** | The beta is only available with paid Cursor plans |
| **Agents are central to their strategy** | They acknowledge agents are changing development |
| **They have deep engineering talent** | Hiring from GitHub (Vicent Martí) shows they're serious |

---

## 6. Connection to My Investigation

| What This Article Shows | What I've Documented |
|-------------------------|----------------------|
| Cursor is building advanced infrastructure | Cursor still traps free users with 1 message → 31-day lockout |
| Cursor has deep engineering resources | Cursor still hides its usage meter |
| Cursor is planning for enterprise scale | Cursor still gaslights users with "you didn't finish Pro setup" emails |
| Cursor is solving technical problems | Cursor ignores ethical problems (hidden limits, deceptive policies) |

> *"Cursor can solve Git scalability, but they can't solve their own credibility problem."*

---

## 7. Conclusion

> *"Cursor's Origin and Continuity show they are capable of solving hard technical problems. But technical excellence doesn't excuse deceptive business practices. They can build a better Git infrastructure while still building a trap for free users. The two aren't mutually exclusive, and that is the problem."*

---

## 8. Statement

> *"Evidence. Truth. Accountability. No threats. No fabrication."*

---

*SuperHero2010 Investigative Unit*

*August 25, 2026*