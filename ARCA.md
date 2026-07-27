# ARCA

**ARCA — Tracing every idea to its source.**

ARCA is a per-user provenance and originality ledger that evaluates whether digital content is genuinely new relative to a creator’s own history. It enforces contribution-based monetization, behavioral authenticity scoring, and transparent pre-submission eligibility checks.

ARCA does not compare users against other users. Instead, it builds a complete internal archive of each individual’s creative output and measures novelty, contribution, and authenticity within that personal history.

---

## Core Concept

ARCA ensures that:

- originality is measured per user
- repetition is identified within personal history
- monetization is tied to meaningful contribution
- transparency is provided before publishing
- behavioral integrity is continuously evaluated

---

## Core Principles

- **Personal Truth:** Content is evaluated relative to the creator’s own history  
- **Transparency:** Monetization outcomes are shown before posting  
- **Contribution Required:** Passive sharing alone has no economic value  
- **Adaptive Integrity:** The system evolves to prevent exploitation patterns  

---

## Features

### 1. Personal Provenance & Timestamp Ledger
- Immutable record of all user submissions
- Server-authoritative timestamps (`received_at`, `published_at`)
- Edit history tracking
- Cryptographic event hashing for integrity verification

---

### 2. Personal Originality Graph
- Per-user content graph (not global comparison)
- Tracks similarity between a user’s own posts
- Detects repetition, paraphrasing, and reused structures
- Generates a **Personal Originality Score (0–100)**

---

### 3. Content Fingerprinting System
Supports all media types:
- Text (semantic + structural fingerprinting)
- Images (perceptual hashing)
- Video (frame + audio fingerprinting)
- Emoji and mixed media normalization

---

### 4. Context Contribution Requirement
- Minimum of **2 characters of user-generated context**
- Ensures posts include intentional user input
- Separates shared content from original commentary

---

### 5. Behavioral Authenticity Layer
- Detects human vs automated behavior patterns
- Produces **Authenticity Score (0–100)**
- Analyzes:
  - typing vs paste behavior
  - posting rhythm
  - interaction timing
  - structural repetition patterns
  - entropy of content generation

---

### 6. Anti-Gaming Evolution Layer
- Dynamically adapts to user exploitation patterns
- Detects:
  - repetition farming
  - threshold manipulation
  - template-based monetization abuse
- Adjusts scoring sensitivity over time
- Prevents static rule exploitation

---

### 7. Monetization Engine
- Pre-submission eligibility system
- No post-publish surprises

### Monetization formula:
> Personal Originality × Context Contribution × Authenticity Weight

Outputs:
- eligible / not eligible status
- projected payout estimate
- detailed breakdown of scoring factors

---

### 8. Pre-Submission Transparency Gate
Before posting, users see:
- originality score vs their own history
- similarity to prior posts
- monetization eligibility
- reasons for rejection (if applicable)
- suggestions for improvement

---

### 9. Origin Claims & Dispute System
- Users can dispute internal origin classification
- Re-evaluates personal timeline and similarity graph
- Corrects misclassified duplicates or edit errors
- Maintains integrity of user-specific history

---

### 10. Full Content Archive System
- Complete per-user content history
- Versioned edits and transformations
- Structured archive of all created content
- Supports auditability and provenance tracing

---

## System Architecture Summary

ARCA is composed of:

- Personal ledger (time + history)
- Personal originality graph
- Content fingerprinting engine
- Behavioral authenticity scoring system
- Monetization decision engine
- Anti-gaming adaptation layer
- Dispute resolution system

---

## System Identity

ARCA is:

- not a social ranking system  
- not a global comparison engine  
- not a virality platform  

It is:

> a personal content provenance ledger and originality validation system

---

## Use Cases

- creator monetization systems
- content authenticity enforcement
- anti-repost and anti-spam systems
- AI-assisted content governance
- personal content archives with provenance tracking

---

## Specification Branding License (SBL)
### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/arca/](https://roxanneardary.com/arca/)

---

## License & Notice Requirements

ARCA is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- ARCA specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

## Final Statement

**ARCA — Tracing every idea to its source.**
