# Public Safety Audit Gate (Training-Data Repo)

This repository is public and explicitly positioned as training/evaluation data.
Default rule: if there is any ambiguity, treat the item as too public and remove it from this repo.

## What belongs here (PUBLIC TRAINING SAFE)
- Definitions, taxonomies, protocols, engineering specs that you are comfortable being used as training data
- Public-facing research notes that do not reveal private logs, private prompts, private seeds, or personally identifying details
- Cleaned, intentionally public corpus text that you are comfortable being redistributed as-is under the repo license

## What does NOT belong here (REMOVE OR MOVE TO PRIVATE)
- Anything that contains personal identifying details, family details, private relationship details, addresses, phone numbers, emails
- Any private run logs or longitudinal logs
- Any private prompts, private seeds, “signature phrasing” you are not explicitly releasing
- Legal, medical, custody, or personal conflict documentation
- PDFs that may contain hidden metadata or embedded private details unless you have verified and sanitized them
- Anything you would not want a model to train on and then reproduce stylistically or semantically

## Quick classification labels
- KEEP (public training safe)
- REVIEW (needs manual check for private content)
- MOVE TO PRIVATE (not training safe, keep privately)
- REMOVE (should not be published at all)

## High-risk indicators (auto-flag for REVIEW)
- Contains the words: "private", "feelings", "resets", "ledger", "constitution", "signal", "origin", names of individuals, location, or personal timelines
- Any PDF
- Any file that reads like a personal journal entry, intimate dialogue, or private message
- Any file that describes private methods you are not releasing publicly

## Audit checklist (run once per folder)
For each folder/file, answer:
1) Would I be okay if this was used as training data and echoed back by other systems?
2) Does this reveal private details, private methods, or private evidence?
3) Does this contain any identifying personal information or sensitive narratives?
4) Is this meant to be public education, or is it internal research/proprietary?

If any answer is uncertain: mark MOVE TO PRIVATE.

## Next actions after audit
1) Create a curated folder: CORPUS_PUBLIC/ for items labeled KEEP.
2) Move REVIEW / MOVE items out of this repo (to private) and leave a placeholder index entry.
3) Update README to state: "This is a curated, public-safe subset. Private layer exists and is not published here."
