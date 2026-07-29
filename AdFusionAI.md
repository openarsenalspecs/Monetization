# AdFusionAI  
**Transient Analysis, Permanent Impact**

AdFusionAI is an advanced, open source, privacy-preserving contextual advertising engine. It analyzes **text, images, and videos** in real-time to generate highly relevant ad recommendations based strictly on the **original content creator's post**.  

All processing occurs **in memory**. No content, logs, embeddings, or user data are ever stored, ensuring full privacy and compliance with ethical standards.

**Attribution:**  
Created by **Roxanne Ardary — [roxanneardary.com](https://www.roxanneardary.com/)**

---

## Overview

AdFusionAI is designed for **social media platforms, blogs, and publishing systems** where contextual advertising must be:

- Accurate and relevant  
- Brand-safe  
- Creator-focused  
- Privacy-first and storage-free  
- Multi-modal across text, image, and video  

The engine matches ads to content **instantly** and **transiently**, without retaining any data.

---

## Key Features

### 1. Multi-Modal Real-Time Content Analysis
- NLP for text meaning extraction  
- Object and scene recognition for images  
- Scene-level video segmentation and interpretation  
- Tone, emotion, and sentiment detection  
- Safety, cultural, and brand-appropriateness analysis  

---

### 2. Creative Gap Filling
- Generates fallback ads aligned with content theme  
- Includes text and optional image  
- Entirely in memory  

---

### 3. Multi-Slot Ad Optimization
- Hero, sidebar, mobile, social card placements  
- Optimizes ad layout per platform  
- Structured metadata returned  

---

### 4. Tone & Mood-Based Targeting
- Humor, inspiration, urgency, calm, celebratory, professional  
- Ensures ad style matches content tone  

---

### 5. Trend & Virality Prediction
- Detects trending topics and viral patterns  
- Avoids unsafe or sensitive trending content  
- Adjusts ad selection dynamically  

---

### 6. “Do Not Monetize” Detection
- Automatically excludes grief, crisis, or sensitive content  
- Supports platform override options  

---

### 7. Object + Scene Depth Understanding
- Detects objects, environments, activities  
- Non-identifying people detection  
- Risk and brand conflict analysis  

---

### 8. Scene-Level Video Intelligence
- Video scene segmentation  
- Scene classification for precise ad matching  
- Multi-scene content analysis  

---

### 9. Creator Style Profiling (In-Memory)
- Writing, visual, and narrative style detection  
- Fully transient, not stored  

---

### 10. Brand Fit Analysis
- Ensures ad tone and subject matter align with creator style  
- Avoids brand conflicts and misalignment  

---

### 11. Ethical Guardrails
- Detects scams, disinformation, hate content, manipulations  
- Suppresses unsafe or unethical ads  

---

### 12. Pluggable Ad Sources
- Supports dynamic partner feeds, JSON ad catalogs, and in-memory ad pools  
- Flexible integration with platform ad infrastructure  

---

### 13. Category-Based Ad Clustering
- Finance, health, travel, education, shopping, entertainment, lifestyle, tech  
- In-memory clusters for fast, relevant matching  

---

### 14. Dynamic Safety Modes
- Standard, strict advertiser, family-friendly, sensitive-topic optimized, culturally-aware  
- Configurable per platform  

---

### 15. Edge & On-Device Deployment
- Cloud, serverless edge, or on-device execution  
- Zero data retention while maintaining real-time performance  

---

### 16. Watermark & Logo Detection
- Detects logos, watermarks, and brand elements  
- Ensures no competitor ad conflicts  

---

### 17. Cultural Sensitivity Engine
- Checks symbols, gestures, attire, holidays, regional norms  
- Avoids inappropriate ad placements globally  

---

### 18. Emotion-Safe Advertising
- Detects distress, grief, anger, fear, vulnerability  
- Adjusts or suppresses ads to avoid intrusive or predatory placements  

---

## Architecture Overview

- **Analyzer:** Multi-modal input understanding  
- **Scene Processor:** Video scene segmentation and classification  
- **Emotion Engine:** Tone and sentiment interpretation  
- **Safety Engine:** Cultural, ethical, and brand safety checks  
- **Ad Matching Core:** Multi-slot, context-aware ad selection  
- **Creative Generator:** Fallback ad generation  
- **Ad Registry:** Transient in-memory ad catalog  
- **API Layer:** Structured ad metadata output  

All modules operate **in-memory only**, with zero persistent storage.

---

## Integration Flow (No Code Examples)

1. Platform detects content upload (text, image, video).  
2. Content is temporarily sent to AdFusionAI in-memory.  
3. Multi-modal analysis runs instantly.  
4. AdFusionAI returns structured ad metadata:
   - Multi-slot placements  
   - Generated fallback ads (if needed)  
   - Tone, mood, and safety flags  
5. Platform renders ads in UI.  
6. All content and analysis are immediately discarded.  

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
  - [https://roxanneardary.com/adfusionai/](https://roxanneardary.com/adfusionai/)  
  
---

## License & Notice Requirements

AdFusionAI is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- AdFusionAI specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
