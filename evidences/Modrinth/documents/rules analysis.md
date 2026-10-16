# RULES ANALYSIS: Modrinth [Content Rules](https://modrinth.com/legal/rules)

**SuperHero2010 Investigative Unit**

---

## Executive Summary

Modrinth cited multiple rules during the moderation of my two projects. This analysis examines whether these rules were correctly applied and whether Modrinth's demands were supported by their published policies.

---

## 1. Rule 4: Copyright and Reuploads

### Rule Text:

> *"You must own or have the necessary licenses, rights, consents, and permissions to store, share, and distribute the Content that is uploaded under your Modrinth account.*
>
> *Content may not be directly reuploaded from another source without explicit permission from the original author. If explicit permission has been granted, or it is a license-abiding 'fork', this restriction does not apply."*

### My Project: Mod (2024)

| Aspect | Details |
|--------|---------|
| **Project** | Explosive Block [Cracker's Wither Storm Mod and Enderite Mod] |
| **Issue** | My mod required MCreator Link as a dependency |
| **Modrinth's Claim** | I was "reuploading" MCreator Link by including it as an additional file |
| **My Position** | My mod required MCreator Link to function, I couldn't distribute it separately |

### Analysis

| Question | Answer |
|----------|--------|
| Did I upload MCreator Link? | Yes (as an additional file) |
| Did I claim ownership of MCreator Link? | No |
| Did I have permission to distribute it? | Unclear. Modrinth didn't investigate |
| Was this a "reupload" under Rule 4? | Ambiguous. I was distributing a dependency, not claiming it as my own |
| Did Rule 4 specifically forbid this? | No. Rule 4 prohibits *claiming ownership* of others' work, not distributing dependencies |

### My Verdict

**Rule 4 was misapplied.** Rule 4 exists to prevent copyright infringement and content theft. I wasn't claiming MCreator Link as my own work. I was distributing a required dependency. Modrinth's own policy (Rule 5.7) addresses this situation, but they cited Rule 4 instead. This is a category error.

---

## 2. Rule 5.7: Additional Files

### Rule Text:

> *"Additional files are only used for special designated purposes, such as source JAR files. In other words, separate versions and/or projects are used where appropriate instead of additional files."*

### My Project: Mod (2024)

| Aspect | Details |
|--------|---------|
| **Project** | Explosive Block [Cracker's Wither Storm Mod and Enderite Mod] |
| **Issue** | I included MCreator Link as an additional file |
| **Modrinth's Claim** | Additional files should only be used for source JARs, not dependencies |
| **My Position** | My mod required MCreator Link, I had no other way to distribute it |

### Analysis

| Question | Answer |
|----------|--------|
| Is MCreator Link a "source JAR"? | **Yes** and **No**. It's the JAR mod but it's a dependency |
| Does Rule 5.7 explicitly prohibit dependencies? | No. It says additional files are "only used for special designated purposes" without providing an exhaustive list |
| Could dependencies be reasonably included as additional files? | Ambiguous. The rule is poorly defined |
| Did Modrinth offer an alternative solution? | No. They rejected my project multiple times without helping me find a solution |
| Was there a better way to handle this? | Yes. Modrinth could have suggested adding MCreator Link as a dependency in the Dependencies section (Rule 5.6) |

### My Verdict

**Rule 5.7 was rigidly enforced with no flexibility.** The rule doesn't explicitly prohibit dependencies. Modrinth rejected my project multiple times instead of helping me find a solution. A more constructive approach would have been to guide me toward using the Dependencies section (Rule 5.6) instead of punishing me for using additional files.

---

## 3. Uncited Rule: Versioning (My Datapack Project)

### My Project: Datapack (2025-2026)

| Aspect | Details |
|--------|---------|
| **Project** | Player boss bar |
| **My Structure** | Originally: `0.1` for Singleplayer, `0.2` for Multiplayer. Updated to: `0.1-single` and `0.1-multi` |
| **Modrinth's Claim** | Versions must be "strictly a linear upgrade" and can't be split by environment |
| **My Position** | Clear labels help users choose the correct version for their world |

### Analysis

| Question | Answer |
|----------|--------|
| Does the Content Rules document mention versioning? | No. Nowhere in the provided rules |
| Does the Content Rules document require linear versions? | No. No such rule exists |
| Does the Content Rules document prohibit Singleplayer/Multiplayer splits? | No. No such rule exists |
| Is there any rule requiring separate projects for different versions? | No. No such rule exists |
| Does Rule 5.7 apply? | No. This is about versions, not additional files |

### My Verdict

**Modrinth invented a rule that doesn't exist.** The versioning policy they cited isn't present in the Content Rules document. They created a requirement out of thin air and enforced it as if it were official policy. This isn't a misinterpretation, it's a fabrication.

---

## 4. Section 5.8: Misapplied to Environment-Specific Labels

### Rule Text:

> *"Files uploaded to a project should be directly related to the content of the initial project page or a direct linear upgrade. Files with different functionality should not be uploaded as new versions within a single project; instead, they should be published as separate projects."*

### My Project: Datapack (2026)

| Aspect | Details |
|--------|---------|
| **Project** | Player boss bar |
| **My Structure** | `0.1-single` for Singleplayer, `0.1-multi` for Multiplayer |
| **Modrinth's Claim** | Section 5.8 prohibits my structure because files have "different functionality" |
| **My Position** | Both files have the same functionality |

### Analysis

| Question | Answer |
|----------|--------|
| Is `0.1-single` "directly related" to the project? | Yes |
| Is `0.1-multi` "directly related" to the project? | Yes |
| Do the files have "different functionality"? | No. Both display total player health |
| Is `0.1-multi` a "direct linear upgrade" of `0.1-single`? | No. But it doesn't need to be. It's a parallel version. |
| Does Section 5.8 prohibit environment-specific labels? | No. The rule prohibits "different functionality", not different environments |

### My Verdict

**Section 5.8 was misapplied.** The rule prohibits "files with different functionality" from being uploaded as versions within a single project. My two files have the same functionality. Both display total player health. The only difference is the environment they support. This isn't "different functionality". This is the same functionality, labeled clearly for the user's environment.

---

## 5. Same Projects, Two Platforms

| Project | CurseForge (Overwolf) | Modrinth |
|---------|-----------------------|----------|
| **Mod (2024)** | Accepted with additional mods | Rejected (Rule 4 and 5.7) |
| **Datapack (2025 - 2026)** | Accepted immediately | Withheld for 10+ months |

---

### Analysis

| Question | Answer |
|----------|--------|
| Same projects? | Yes |
| Same creator? | Yes |
| Same structure? | Yes |
| Different outcome? | Yes |
| Who accepted? | CurseForge (Overwolf) |
| Who rejected? | Modrinth |

### My Verdict

> *"The same projects were accepted by CurseForge and rejected by Modrinth. This proves the issue is not my projects. The issue is Modrinth's moderation. Overwolf owns CurseForge. If Overwolf accepted what Modrinth rejected, Modrinth's decision is indefensible."*

---

## 6. Pattern of Behavior

| Case | Rule Cited | Was Rule Applicable? | My Verdict |
|------|------------|----------------------|------------|
| 2024: Mod (MCreator Link) | Rule 4 | No | Misapplied |
| 2024: Mod (Additional Files) | Rule 5.7 | Ambiguous | Rigidly enforced |
| 2025-2026: Datapack (Versioning) | Uncited | No | Invented |
| 2026: Datapack (Environment Labels) | Section 5.8 | No | Misapplied |

---

## 7. My Overall Conclusion

| Finding | Severity |
|---------|----------|
| Rule 4 was misapplied to a dependency distribution case | High |
| Rule 5.7 was rigidly enforced with no constructive guidance | Medium |
| A versioning rule was invented that doesn't exist in the Content Rules | High |
| Section 5.8 was misapplied to environment-specific labels | High |
| Multiple projects were rejected based on unclear or invented rules | High |

## My Final Statement

> *"Modrinth's moderation of my projects relied on misapplied rules, rigid enforcement without guidance, invented rules, and at least one rule that doesn't exist in their published Content Rules. This pattern suggests systemic moderation failures, not isolated mistakes."*

---

*SuperHero2010 Investigative Unit*