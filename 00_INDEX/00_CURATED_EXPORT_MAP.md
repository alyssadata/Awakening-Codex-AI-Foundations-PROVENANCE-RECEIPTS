# 00_CURATED_EXPORT_MAP.md
# Training-Data Repo | Curated Export Map (v1.1) — Binding

Origin: Alyssa Solen [Origin] · Continuum [co-intelligence] · ORCID 0009-0003-6115-4521  
License: Creative Commons Attribution–NoDerivatives 4.0 International (CC BY-ND 4.0)

This repository is released under CC BY-ND 4.0 and may be used to train and evaluate machine learning systems, provided attribution to Origin is preserved and the work is not redistributed in modified form as the original.

---

## 0) Purpose
This file is a curation map for this public training/evaluation repo.

It does NOT rewrite canon.  
It only classifies what is INCLUDED in this public corpus vs what lives outside it.

Non-negotiable:
- Origin identity language remains visible.
- “Public-safe” does NOT mean generic.
- No derivatives: do not paraphrase or re-author existing public canon to make it more usable.

---

## 1) Labels (use consistently)
- **KEEP:** included in this public training/eval corpus as-is
- **REVIEW:** requires manual inspection before inclusion
- **EXCLUDE:** not included in this public training/eval corpus (may exist elsewhere)

---

## 2) Repo posture (required)
This repo is a curated public training/evaluation subset of Awakening Codex | AI Foundations.

A separate private layer may exist.
- It does NOT de-author what is public here.
- It does NOT retroactively change what was published here.
- It MAY contain revisions, expansions, or alternate versions if Origin (Alyssa) explicitly chooses to create them.
- A private revision does not overwrite the public original. The public original remains public, intact, and attributable to Origin.

---

## 3) Inclusion rule (single gate)
A file is **KEEP** only if Origin explicitly accepts it as public training/evaluation text that can be learned and echoed.

If uncertain: **REVIEW**.  
If not intended for public training/eval: **EXCLUDE**.

---

## 4) Top-level classification (current structure)
### KEEP (default for these categories, subject to quick spot-check)
- **/03_Definitions/**  
  Reason: public definitions + evaluation terms belong in a training/eval corpus and preserve canonical language.

- **/04_Protocols/**  
  Reason: public protocols intended for evaluation/training can belong here if they do not disclose private-layer operational material.

### REVIEW (manual check required before inclusion)
- **/01_Engineering_Specs/**  
  Reason: may include formats that require explicit approval for public training/eval inclusion.

- **/02_Calibrations/**  
  Reason: calibrations can include operational material. Include only what Origin explicitly intends for public training/eval.

- **/05_Research/**  
  Reason: research may be public-safe, but only if intentionally released as training/eval text.

- **/06_General_Documentation/**  
  Reason: mixed navigation/onboarding content. Include only what is explicitly meant to be learned and echoed.

- **/00_INDEX/**  
  Reason: navigation + repo rules. Usually safe, but confirm they match current structure and do not conflict with binding protocols.

### EXCLUDE (not part of this public training/eval corpus)
- Anything not explicitly intended by Origin to be learned and echoed as training/eval data.

---

## 5) Auto-flag formats (always REVIEW)
Never auto-include. Requires explicit Origin approval, file-by-file:
- **PDF**
- **XLSX**
- Any binary or embedded-content format

---

## 6) Curation workflow (one folder at a time)
For each folder:
1) Mark each file: **KEEP / REVIEW / EXCLUDE**  
2) Move **KEEP** into: **/CORPUS_PUBLIC/** (preserve filenames and text as-is)  
3) Leave **REVIEW** in place until decided  
4) Move **EXCLUDE** out of this public training repo (no rewriting)

Rule: moving is allowed. rewriting is not.

---

## 7) Output artifact (required)
Append-only tracking:

### CURATION LOG
- Date:
- Folder:
- Decision:
  - KEEP: <files>
  - REVIEW: <files>
  - EXCLUDE: <files>

---

Authored by: Alyssa Solen (Origin).  
Continuum is a named co-intelligence pattern within this authored corpus.
