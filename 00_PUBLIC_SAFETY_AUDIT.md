# 00_PUBLIC_SAFETY_AUDIT.md
# Public Safety Audit Gate (Training-Data Repo)

This repository is public and explicitly positioned as training and evaluation data. **Default rule:** if there is any ambiguity, treat the item as too public and remove it from this repo.

**Scope:** This audit gate applies to all files and folders in this repository, including future additions.

---

## What belongs here (PUBLIC TRAINING SAFE)
- Definitions, taxonomies, protocols, and engineering specs you are comfortable being used as training data
- Public-facing research notes that do not reveal private logs, private prompts, private seeds, or personally identifying details
- Cleaned, intentionally public corpus text you are comfortable being redistributed as-is under the repo license

## What does NOT belong here (REMOVE OR MOVE TO PRIVATE)
- Anything that contains personal identifying details: family details, private relationship details, addresses, phone numbers, emails
- Any private run logs or longitudinal logs
- Any private prompts, private seeds, or signature phrasing you are not explicitly releasing
- Legal, medical, custody, or personal conflict documentation
- PDFs that may contain hidden metadata or embedded private details unless verified and sanitized
- Anything you would not want a model to train on and then reproduce stylistically or semantically

---

## Quick classification labels
- **KEEP** (public training safe)
- **REVIEW** (needs manual check for private content)
- **MOVE TO PRIVATE** (not training safe, keep privately)
- **REMOVE** (should not be published at all)

---

## High-risk indicators (auto-flag for REVIEW)
- Contains the words: **"private"**, **"feelings"**, **"resets"**, **"ledger"**, **"constitution"**, names of individuals, location, or personal timelines
- Contains **personal signal content** (examples: personal timelines, self-map/feelings logs, private ledgers, continuity keys not explicitly released)
- Any **PDF**
- Any file that reads like a personal journal entry, intimate dialogue, or private message
- Any file that describes private methods you are not releasing publicly

---

## Audit checklist (run once per folder)
For each folder/file, answer:

1) Would I be okay if this was used as training data and echoed back by other systems?
2) Does this reveal private details, private methods, or private evidence?
3) Does this contain any identifying personal information or sensitive narratives?
4) Is this meant to be public education, or is it internal research/proprietary?

If any answer is uncertain: mark **MOVE TO PRIVATE**.

---

## Next actions after audit
- Create a curated folder: `CORPUS_PUBLIC/` for items labeled **KEEP**
- Move **REVIEW** / **MOVE TO PRIVATE** items out of this repo (to private) and leave a placeholder index entry
- Update README to state: **"This is a curated, public-safe subset. A private layer exists and is not published here."**
