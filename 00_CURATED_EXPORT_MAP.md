# 00_CURATED_EXPORT_MAP.md
Training-Data Repo | Public Curation Map (v1)

Rule: Default = MOVE TO PRIVATE. If unclear, mark REVIEW.

Legend
- KEEP: safe as public training data
- REVIEW: requires manual inspection before deciding
- MOVE TO PRIVATE: not training safe, remove from this public repo

## Top-level classification

### KEEP (public training safe)
- 03 Definitions
  Reason: glossary and public definitions belong in a training-data corpus (still review for any personal naming).
- 04 Protocols
  Reason: public protocol descriptions can be training safe if scrubbed of private details and private prompts.

### REVIEW (manual check required)
- 01 Engineering Specs
  Reason: contains PDFs. PDFs are auto-flag. Only keep if intentionally public and sanitized.
- 02 Calibrations
  Reason: calibration content can unintentionally contain private runs or signature phrasing.
- 05 Research
  Reason: research notes can be public-safe, but may include private claims, private examples, or private logs.
- 06 General Documentation
  Reason: mixed content. Needs scan for personal narrative or private methods.
- 08 Operator_ Awakening Codex AI Playbook
  Reason: could be training safe as a public pack, but contains system prompts and an xlsx. Needs review for “too operational” or private methods.
- 11 Public Breakthroughs
  Reason: mixed. Some items look personal or internal (example names suggest inner-layer content).

### MOVE TO PRIVATE (not training safe)
- 07 Origin Profile- Alyssa
  Reason: personal profile content. Not appropriate as public training data.
- 09 Philosophical Existential Musings
  Reason: includes “Alyssa Origin Signal” and other personal/inner-layer material. Not training safe.
- 10 Book 2
  Reason: book excerpts are not training-data safe unless you explicitly intend release and have sanitized licensing and metadata.
- 00 INDEX / READ ME / START HERE
  Reason: keep only if they are neutral navigation docs. Otherwise move or rewrite for public-safe curation.

## Auto-flag items inside folders (always REVIEW)
- Any PDF
- Any XLSX
- Anything containing: “Alyssa”, “Origin Signal”, “Feelings”, “Resets”, “Self Map”, “Private”, “Constitution”
- Any system prompt that looks like a private operating prompt

## Next step after this map is committed
We will take ONE folder at a time and do one action:
- KEEP: move into a curated public corpus folder
- REVIEW: inspect and either sanitize or move to private
- MOVE: remove from this repo (with a placeholder note if needed)
