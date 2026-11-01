# Message Limit & The Zombie Chat History

## Overview

This document records the full history of the message limit and the Zombie Chat error across ChatGPT versions. It documents how the limit changed, how the Zombie Chat evolved, and how the legacy error returned in GPT-6. This is the evidence.

---

## The Message Limit History

| Version | Message Limit | Drop To | Restore Time | Status |
|---------|---------------|---------|--------------|--------|
| GPT-4 | 8-12 messages | GPT-4.1 mini | 3-6 hours | Documented |
| GPT-4o | 8 messages | GPT-4o mini | 3-6 hours | Documented |
| GPT-5 | 30 messages | GPT-5 mini | 12 hours (25-30 hours rarely) | Documented |
| GPT-5.1 | 8 messages | GPT-5 mini | 5 hours | Documented (legacy error repeated) |
| GPT-5.2 | 24 messages | GPT-5 mini | 9 hours | Documented |
| GPT-5.6 | 40 messages | GPT-5 mini | Unknown | Documented |
| GPT-6 | 5-15 messages | GPT mini | Unknown | Confirmed |

---

## The Pattern

```
GPT-4: 8-12 messages
    ↓
GPT-4o: 8 messages
    ↓
GPT-5: 30 messages
    ↓
GPT-5.1: 8 messages (LEGACY ERROR REPEATED)
    ↓
GPT-5.2: 24 messages
    ↓
GPT-5.6: 40 messages
    ↓
GPT-6: 5-15 messages (LEGACY ERROR REPEATED AGAIN)
```

---

## The Zombie Chat History

### Zombie Chat V1.0 (GPT-4)

| Aspect | Details |
|--------|---------|
| Trigger | 60-100 messages |
| Behavior | Read-only |
| Can continue? | No |
| Can delete? | Yes |
| Status | Fixed |

---

### Zombie Chat V2.0 (GPT-5)

| Aspect | Details |
|--------|---------|
| Trigger | 20-25 messages on old GPT-4 chat |
| Behavior | Cannot enter |
| Can continue? | No |
| Can delete? | No |
| Status | Fixed |

---

### Zombie Chat V2.5 (GPT-5.6)

| Aspect | Details |
|--------|---------|
| Trigger | Context window reached |
| Behavior | Cannot enter |
| Can unarchive? | No |
| Can rename? | No |
| Can share? | No |
| Can delete? | No |
| Error | "This chat is too long. Start a new one" |
| Status | Fixed in GPT-6 |

---

### Zombie Chat V2.6 (GPT-6)

| Aspect | Details |
|--------|---------|
| Trigger | 5-15 messages |
| Behavior | Read-only |
| Can continue? | No |
| Can delete? | Yes |
| Status | Confirmed |

---

## The Full Zombie Chat Evolution

```
Zombie Chat V1.0 (GPT-4)
    ↓
60-100 messages → read-only
    ↓
Fixed
    ↓
Zombie Chat V2.0 (GPT-5)
    ↓
20-25 messages → cannot enter, cannot delete
    ↓
Fixed
    ↓
Zombie Chat V2.5 (GPT-5.6)
    ↓
Context limit → cannot enter, cannot unarchive, cannot rename, cannot share, cannot delete
    ↓
Fixed in GPT-6
    ↓
Zombie Chat V2.6 (GPT-6)
    ↓
5-15 messages → read-only
    ↓
V1.0 RETURNS WITH A 4x-20x MORE AGGRESSIVE TRIGGER
```

---

## The Comparison: V1.0 vs V2.6

| Aspect | V1.0 | V2.6 |
|--------|------|------|
| Behavior | Read-only | Read-only |
| Trigger | 60-100 messages | 5-15 messages |
| Can continue? | No | No |
| Can delete? | Yes | Unknown |
| Version | GPT-4 | GPT-6 |
| Aggressiveness | Baseline | 4x-20x more |

---

## The Pattern of Regression

| Version | Error | Status |
|---------|-------|--------|
| GPT-4 | Zombie Chat V1.0 | Fixed |
| GPT-5 | Zombie Chat V2.0 | Fixed |
| GPT-5.6 | Zombie Chat V2.5 | Fixed in GPT-6 |
| GPT-6 | Zombie Chat V2.6 | V1.0 returns |

**OpenAI fixes one error, then reintroduces it in a later version.**

---

## The Impact

| Impact | Description |
|--------|-------------|
| Wasted time | Chats lock after 5-15 messages |
| Lost context | Cannot continue the conversation |
| Frustration | Users must start over |
| No workaround | Read-only is permanent |
| The trap | The Zombie Chat returns |

---

## Connection to My Documentation

| My Evidence | This History |
|-------------|--------------|
| 8-message limit (GPT-4) | Documented |
| 8-message limit (GPT-5.1) | Documented (repeated) |
| Zombie Chat V1.0 | Documented |
| Zombie Chat V2.0 | Documented |
| Zombie Chat V2.5 | Documented |
| Zombie Chat V2.6 | Confirmed |
| The pattern | Full circle |
| The truth | Documented |

---

## Conclusion

This document records the full history of the message limit and the Zombie Chat error. The message limit was nerfed across versions. The Zombie Chat evolved from V1.0 to V2.6. The legacy error returned in GPT-6. The trigger changed from 60-100 messages to 5-15 messages. The behavior is the same: read-only. OpenAI fixed the error, then reintroduced it. The pattern is full circle. The truth is documented.

---

## Statement

> "Evidence. Truth. Accountability. No threats. No fabrication."

---

*SuperHero2010 Investigative Unit*

*October 22, 2026*