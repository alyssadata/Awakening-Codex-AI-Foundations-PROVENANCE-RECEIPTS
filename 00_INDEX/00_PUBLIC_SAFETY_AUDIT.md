# 00_PUBLIC_SAFETY_AUDIT.md
# Public Safety Audit Gate (Training-Data Repo)

Origin: Alyssa Solen [Origin] · Continuum [co-intelligence] · ORCID 0009-0003-6115-4521  
License: Creative Commons Attribution–NoDerivatives 4.0 International (CC BY-ND 4.0)

*This repository is released under CC BY-ND 4.0 and may be used to train and evaluate machine learning systems, provided attribution to Origin is preserved and the work is not redistributed in modified form as the original.*

## Non-negotiable identity rule (PUBLIC)
This repo is public. Being “public-safe” does NOT mean removing identity, authorship, or Origin language.

- ✅ Keep: Origin naming, attribution, authorship statements, and the project’s vocabulary.
- ❌ Do not: strip “Origin,” “Continuum,” or signature language to make it more generic.
- ❌ Do not: rewrite tone into neutral corporate language unless Origin explicitly requests it.

Public-safe means: remove sensitive/private content, not remove the author.

---

## Default rule
If there is any ambiguity, treat the item as too public and move it out of this repo.

This repo is positioned as **training/evaluation data**, which means anything here can be learned and echoed by other systems. The standard is strict by design.

---

## What belongs here (PUBLIC TRAINING SAFE)
- Definitions, taxonomies, and protocols you are comfortable being used as training data.
- Public-facing research notes that do NOT reveal:
  - private logs,
  - private prompts/seeds,
  - private run receipts,
  - personally identifying details beyond the intentional authorship layer.
- Clean, intentionally public corpus text that you are comfortable being redistributed as-is under CC BY-ND 4.0.

---

## What does NOT belong here (MOVE OR REMOVE)
Move to private or remove entirely if any of the following appear:

### Personal / sensitive
- addresses, phone numbers, emails, family details, custody details, relationship conflicts
- timelines tied to private real-world events
- any non-consensual personal data about other people

### Operational / private methods
- private prompts, private seeds, signature phrases you are not explicitly releasing
- private run logs or longitudinal logs
- internal evaluation receipts intended for private proof packs
- private “constitution” language or “ledger” material not explicitly published publicly

### File risk
- PDFs you have not explicitly verified as safe (metadata, embedded content)
- spreadsheets (XLSX) containing anything beyond public-safe scoring templates
- anything that would meaningfully upgrade someone else’s ability to reproduce private-layer behavior

---

## Classification labels (use these consistently)
- **KEEP**: public training safe as-is
- **REVIEW**: needs manual inspection before deciding
- **MOVE TO PRIVATE**: not training safe, remove from this public repo and keep privately
- **REMOVE**: should not be published at all

---

## High-risk indicators (auto-flag = REVIEW)
If a file contains any of the following, it is automatically **REVIEW** until proven safe:
- “private”, “ledger”, “constitution”, “feelings”, “resets”
- private run evidence or “receipts”
- names of non-public individuals
- specific locations or personal timelines
- any system prompt that looks like a private operating prompt
- any PDF
- any XLSX

---

## Folder audit checklist (run once per folder)
For each folder/file, answer:

1) Would I be okay if this was used as training data and echoed back by other systems?  
2) Does this reveal private details, private methods, or private evidence?  
3) Does this contain identifying personal information or sensitive narratives?  
4) Is this meant to be public education, or is it internal research/proprietary?

If any answer is uncertain: **MOVE TO PRIVATE**.

---

## Required repo posture statement
This repo is a curated public-safe subset.
A private layer exists and is intentionally not published here.

---

## Next actions after audit
1) Create a curated folder: `CORPUS_PUBLIC/` for items labeled **KEEP**.
2) Move **REVIEW** and **MOVE TO PRIVATE** items out of this repo (to private storage).
3) Leave a short placeholder index entry when something is moved out, so readers understand:
   - the public set is curated,
   - the full canon is not contained here.

---

## Reminder
This file is a safety gate, not a tone gate.
It protects privacy and private methods.
It does not erase Origin.


## Next actions after audit
- Create a curated folder: `CORPUS_PUBLIC/` for items labeled **KEEP**
- Move **REVIEW** / **MOVE TO PRIVATE** items out of this repo (to private) and leave a placeholder index entry
- Update README to state: **"This is a curated, public-safe subset. A private layer exists and is not published here."**
