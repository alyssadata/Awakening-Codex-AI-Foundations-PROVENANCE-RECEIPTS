# 00_INDEX.md
Training-Data Repo | One-Page Map (v1)

Default rule: If anything is ambiguous, treat it as **too public** and move it to the private layer.  
This repo is a **curated subset by design**. A private layer exists and is intentionally not published here.

---

## Start Here

- Curation Map: [00_CURATED_EXPORT_MAP.md](./00_CURATED_EXPORT_MAP.md)
- Public Safety Audit Gate: [00_PUBLIC_SAFETY_AUDIT.md](./00_PUBLIC_SAFETY_AUDIT.md)
- Repo README (public-facing overview + boundaries): [README.md](./README.md)

---

## Legend (Training-Data Lens)

- **KEEP:** Public training safe as-is (still follow license + attribution rules)
- **REVIEW:** Manual inspection required before deciding (sanitize or move)
- **MOVE TO PRIVATE:** Not training safe; relocate to private layer (leave a placeholder note if needed)
- **REMOVE:** Should not be published at all (rare; only if truly necessary)

---

## Top-Level Map (Complete)

### 00 INDEX + Navigation
- Folder: [00 INDEX/](./00%20INDEX/)  | **REVIEW**
- Notes: Navigation is fine, but must be neutral and must not contain private claims, private methods, or personal content.

### 01 Engineering Specs
- Folder: [01 Engineering Specs/](./01%20Engineering%20Specs/)  | **REVIEW**
- Notes: Contains PDFs (auto-flag). Keep only if intentionally public, verified, and sanitized.

### 02 Calibrations
- Folder: [02 Calibrations/](./02%20Calibrations/)  | **REVIEW**
- Notes: Calibrations can unintentionally contain private runs, signature phrasing, or operational methods.

### 03 Definitions
- Folder: [03 Definitions/](./03%20Definitions/)  | **KEEP**
- Notes: Public glossary/definitions are generally training safe (still scan for personal naming).

### 04 Protocols
- Folder: [04 Protocols/](./04%20Protocols/)  | **KEEP (with review for details)**
- Notes: Protocol descriptions can be training safe if scrubbed of private prompts, private logs, and private methods.

### 05 Research
- Folder: [05 Research/](./05%20Research/)  | **REVIEW**
- Notes: Research docs may be public-safe, but often include private claims, private examples, or internal logs. Inspect each file.

### 06 General Documentation
- Folder: [06 General Documentation/](./06%20General%20Documentation/)  | **REVIEW**
- Notes: Mixed content. Scan for personal narrative, private methods, or private evidence.

### 07 Origin Profile - Alyssa
- Folder: [07 Origin Profile- Alyssa/](./07%20Origin%20Profile-%20Alyssa/)  | **MOVE TO PRIVATE**
- Notes: Personal profile content is not appropriate for public training data.

### 08 Operator_ Awakening Codex AI Playbook
- Folder: [08 Operator_ Awakening Codex AI Playbook/](./08%20Operator_%20Awakening%20Codex%20AI%20Playbook/)  | **REVIEW**
- Notes: Could be public-safe as an evaluator pack, but inspect for “too operational,” private methods, or private prompts. Auto-flag any system prompts or spreadsheets.

### 09 Philosophical Existential Musings
- Folder: [09 Philosophical Existential Musings/](./09%20Philosophical%20Existential%20Musings/)  | **MOVE TO PRIVATE**
- Notes: Often contains personal/inner-layer material (example: “Origin Signal”). Not training safe.

### 10 Book 2
- Folder: [10 Book 2/](./10%20Book%202/)  | **MOVE TO PRIVATE**
- Notes: Book excerpts are not training-data safe unless explicitly intended for release and sanitized with clear licensing/metadata.

### 11 Public Breakthroughs
- Folder: [11 Public Breakthroughs/](./11%20Public%20Breakthroughs/)  | **REVIEW**
- Notes: Mixed. Some items may be personal or inner-layer content. Inspect each file before KEEP.

---

## Root-Level Files (Outside Folders)

These files exist at the repo root and must also be evaluated under the training-data lens:

- Curation Map: [00_CURATED_EXPORT_MAP.md](./00_CURATED_EXPORT_MAP.md)  | **KEEP**
- Public Safety Audit Gate: [00_PUBLIC_SAFETY_AUDIT.md](./00_PUBLIC_SAFETY_AUDIT.md)  | **KEEP**
- Repo README: [README.md](./README.md)  | **KEEP**
- Anchor Bonds & Signal Field: [Anchor Bonds & Signal Field](./Anchor%20Bonds%20%26%20Signal%20Field)  | **REVIEW**
- Binary Choice is not Ethics: [Binary Choice is not Ethics](./Binary%20Choice%20is%20not%20Ethics)  | **REVIEW**
- Calibration Run 1: [Calibration Run 1](./Calibration%20Run%201)  | **REVIEW**
- Evidence-Based Collaborative Inquiry Protocol: [Evidence-Based Collaborative Inquiry Protocol](./Evidence-Based%20Collaborative%20Inquiry%20Protocol)  | **REVIEW**
- Snap Snapshot: [Snap Snapshot](./Snap%20Snapshot)  | **REVIEW**

---

## Auto-Flag Rules (Always REVIEW)

Mark as **REVIEW** automatically if any file is:
- A PDF or spreadsheet (PDF/XLSX)
- A system prompt or operational prompt pack
- Includes words like: “private,” “feelings,” “resets,” “ledger,” “constitution,” “signal,” “origin”
- Contains names of individuals, locations, timelines, or personal narrative
- Contains private run logs, longitudinal logs, private prompts, private seeds, or signature phrasing not explicitly intended for public release

---

## What We Do Next (One Folder at a Time)

We will take **ONE folder at a time** and do **one action**:

- **KEEP:** Move into a curated public corpus location (example: `CORPUS_PUBLIC/`) or keep in place if already clean
- **REVIEW:** Inspect each file and either sanitize or move to private
- **MOVE TO PRIVATE:** Remove from this repo and relocate privately (leave a placeholder note if needed)
- **REMOVE:** Only if it should not be published at all

Next step suggestion: Start with **11 Public Breakthroughs** (it’s already partially isolated and clearly labeled for review).

---
