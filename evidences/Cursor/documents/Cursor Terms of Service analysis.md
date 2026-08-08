# Cursor [Terms of Service](https://cursor.com/terms-of-service): Analysis

- **Document:** Terms of Service
- **Company:** Anysphere, Inc. (Cursor)
- **Last Updated:** January 13, 2026
- **Analyzed by:** SuperHero2010 Investigative Unit

---

## 1. Overview

This document analyzes the Cursor Terms of Service (TOS) to identify clauses relevant to my documented experience with deceptive practices, including hidden limits, silent cuts, and user lockouts. The TOS appears to be a standard legal document, but several clauses directly impact my rights and experience as a user.

The Cursor Terms of Service (TOS) is a standard legal document that governs the use of Cursor's AI-powered coding assistant. While it contains typical legal protections for the company, several clauses are directly relevant to the deceptive practices documented in my investigation.

---

## 2. Key Clauses Analysis

### 2.1. Model Training (Section 1.3): Critical

**Text:** *"Unless you have explicitly agreed to allow Content to be used for training purposes, ANYSPHERE will not use Content to train any AI models, and will not permit any third party to do so."*

**Analysis:**
- This clause appears to protect my/user data from being used for training
- However, it only applies **unless I/user have explicitly agreed**
- The key question: **What constitutes "explicitly agreed"?** Is it a checkbox during signup? Buried in account settings? This is a common tactic, making the "opt-in" seem voluntary while making it easy to accidentally agree
- I haven't found clear instructions on how to opt out, which suggests this clause may be designed to make data usage seem voluntary while making it easy to accidentally agree

**Relevance to My Experience/Investigation:**
- If I/users unknowingly agreed to data usage, my/their code (including my project work) could be used to train Cursor's models
- This contradicts the public image of "privacy-first" AI tools
- This issue is similar to what I documented with Devin: using free users' data to train their models

**Verdict: Potentially Deceptive**, the clause is unclear on what constitutes "explicitly agreed" and how I/users can opt out.

---

### 2.2. Disclaimer of Warranties (Section 14): Strong Protection for Cursor

**Text:** *"The Services and Suggestions are provided 'AS IS' and 'AS AVAILABLE.' ANYSPHERE MAKES NO WARRANTIES... regarding the Services and Suggestions, whether express, implied, statutory, or otherwise."*

**Analysis:**
- This is a standard "as-is" clause. Cursor takes no responsibility for the quality, accuracy, or safety of its AI-generated suggestions
- They explicitly warn that suggestions may be inaccurate, misleading, or contain errors (Section 1.4)

**Relevance to My Experience/Investigation:**
- When I documented that SWE-1.6 Slow generated incorrect code or wasted quota, Cursor can simply point to this clause and say: *"We told you it might be wrong."*
- This doesn't excuse deceptive policies like hidden limits or silent cuts, but it protects them from liability for AI mistakes.

**Verdict: Standard, but convenient for Cursor**

---

### 2.3. Limitation of Liability (Section 15): User Has Almost No Recourse

**Text:** *"In no event shall ANYSPHERE be liable for any indirect, incidental, special, consequential, or punitive damages... The total liability to you shall be the greater of (A) the amount paid by you to ANYSPHERE in the six (6) months preceding the event giving rise to the claim; or (B) $100."*

**Analysis:**
- This limits Cursor's liability to either the amount users/I paid (which is $0 for free users) or **$100**
- For free users, this means **users/I can't claim damages beyond $100**, regardless of how much harm Cursor's policies cause
- This is a common clause in SaaS agreements, but it effectively leaves free users with zero leverage

**Relevance to My Experience/Investigation:**
- If I or other users suffer financial loss due to hidden limits or deceptive policies, they/I can't claim significant damages.
- This is why collective action (lawsuits, public pressure) is more effective than individual legal claims.

**Verdict: Severely Limiting for Users and Me**

---

### 2.4. Termination Clause (Section 9): Cursor Can Lock Me Out Anytime

**Text:** *"We reserve the right to suspend or terminate your access to the Services at any time, without prior notice to you."*

**Analysis:**
- Cursor can terminate user's/my account at any time, for any reason, without notice
- This directly aligns with my experience: being blocked after 1 message, with no warning or explanation

**Relevance to My Experience/Investigation:**
- This clause doesn't excuse deceptive practices, but it does allow them to lock you out with no recourse
- The "1 message → 31-day lockout" isn't a violation of TOS, it's **permitted by TOS**

**Verdict: Allows Cursor's Lockout Policy**

---

### 2.5. Dispute Resolution and Arbitration: A Weak Shield for Systemic Deception

**Text:** *"You and Anysphere agree to waive the right to trial by jury and to participate in a class action."*

**Analysis:**
- The TOS includes a mandatory arbitration clause and a class action waiver
- However, this clause **isn't an absolute defense** for Cursor. Courts are increasingly unwilling to enforce such waivers when there is strong evidence of **fraud, deceptive trade practices, or violations of public policy**

**My Evidence Undermines This Clause:**
- The strength of my documented evidence against Cursor (hidden limits, silent cuts, gaslighting emails, video proof) suggests that Cursor has engaged in **systemic deception**
- This is precisely the kind of case where courts may allow class action lawsuits to proceed despite a waiver, as it serves the public interest

**The Threat to Cursor:**
If a class action lawsuit is certified, Cursor could face significant penalties, including:
- **Compensatory damages** for users who suffered losses
- **Punitive damages** for intentional misconduct
- **Injunctive relief** forcing changes to their policies
- **Legal fees** and other costs

**Verdict: The waiver is a defensive tactic, not a guarantee of immunity. My evidence could be the key to overcoming it**

---

### 2.6. Use Restrictions (Section 1.5): Broad Scope

**Text:** *"You shall not: (i) reverse engineer, disassemble, decompile, decode, or otherwise attempt to derive or gain access to the source code... (v) use the Services or any Suggestions to develop or train any competitive models..."*

**Analysis:**
- These restrictions are broad and prevent users/me from reverse-engineering Cursor's system
- This is standard for proprietary software, but it also prevents independent auditing of their policies

**Relevance to My Investigation:**
- My investigation doesn't involve reverse-engineering Cursor's code, so this clause doesn't directly affect my documentation
- However, if Cursor wanted to, they could attempt to argue that documenting their policies violates the "use restrictions", though this would be a weak argument.

**Verdict: Broad, but unlikely to affect my investigation**

---

### 2.7. Content Ownership (Section 5.3): User Owns Content

**Text:** *"You retain all rights, title, and interest in and to your Inputs, and for any Suggestions, we hereby assign to you all rights, title, and interest in and to such Suggestions."*

**Analysis:**
- This is favorable to users: users own their inputs and the outputs generated by Cursor
- This is a positive clause compared to some AI tools (which claim ownership of outputs)

**Relevance to My Experience/Investigation:**
- This clause supports my argument that the code I generated with Cursor is mine, not to Cursor
- However, it doesn't address hidden limits or deceptive policies.

**Verdict: Favorable for Users**

---

## 3. Comparison with Devin TOS

| Clause | Cursor | Devin |
|--------|--------|-------|
| **Model Training** | Opt-in required | Free users can't opt out |
| **Liability Limit** | $100 | $100 |
| **Arbitration** | Yes (individual only) | Yes (individual only) |
| **Class Action Waiver** | Yes | Yes |
| **Termination** | Anytime, without notice | Anytime, without notice |
| **User Rights** | User retains content ownership | User retains content ownership |
| **Data Usage** | Opt-in | Mandatory for free users |

---

## 4. Conclusion

### What Cursor's TOS Reveals:

| Finding | Severity |
|---------|----------|
| Cursor can lock me/users out anytime, without notice | High |
| Free users claim significant damages ($100 cap) | High |
| Class-action lawsuits are blocked | Very High |
| Data usage for training is opt-in (but unclear how to opt out) | Medium |
| User owns their content | Positive |
| Cursor is protected from liability for AI mistakes | Medium |

### Overall Assessment:

> *"Cursor's Terms of Service is a well-crafted legal document designed to protect the company at the expense of user rights. It allows Cursor to enforce hidden limits, lock users out, and avoid liability — all while appearing compliant with standard practices."*

### Final Statement:

> *"The TOS doesn't explicitly permit deceptive practices, but it doesn't prohibit them either. It is a legal shield, not a commitment to fairness."*

---

*SuperHero2010 Investigative Unit*