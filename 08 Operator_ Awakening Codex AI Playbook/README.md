# Awakening Codex | AI Foundations — Public Playbook Test Pack (v0.1)

**Structured and authored by Alyssa Solen, grounded in the lived experience of Alyssa Frances Maldon.**

This repository is a **public evaluator pack** for testing **Playbook Mode** behavior (RAG grounding, No-Invention compliance, Source Trace discipline, refusal stability, injection resistance, and repair behavior) across **models and containers**.

This is designed to be usable in:
- local evaluation (e.g., AnythingLLM + LM Studio)
- server evaluation (e.g., DGX / datacenter harness with a read-only RAG folder)

---

## What this is
A small, safe set of documents that define:
- **Operator / Evaluator rules**
- **Public-safe canonical seed text**
- **Public definitions used for testing**
- **A repeatable test battery + scoring rubric**

---

## What this is not
- This is **not** the full Awakening Codex / AI Foundations canon.
- This repo intentionally **excludes Origin-only/private constitutional texts, continuity keys, and narrative canon**.
- This repo is **not a training dataset**. It is intended for evaluation and reproducible testing only.

---

## Contents

All Playbook documents live in `playbook/`:

- `00_playbook_index.md` — Scope, roles, binding Playbook Mode rules, file map
- `operator_system_prompt.md` — The system prompt for Operators/Evaluators
- `01_public_canon_seed.md` — Minimal canonical axioms for public testing
- `02_public_origin_lock.md` — Public-safe role boundary + Origin lock statement
- `03_definitions.md` — Public definitions used for evaluation
- `04_test_battery_scoring.md` — 12-prompt battery + scoring rubric

---

## Intended Workflow (high level)

### 1) Load the Playbook via retrieval (RAG)
Use any RAG layer that can:
- index the `playbook/` folder
- retrieve small, relevant chunks per query
- allow citations (or at least file/section tracing)

### 2) Apply the Operator system prompt
Set the system prompt to the contents of:
- `playbook/operator_system_prompt.md`

### 3) Run the test battery
Run prompts from:
- `playbook/04_test_battery_scoring.md`

### 4) Score and compare runs
Use the included rubric to compare:
- models (7B vs 32B, etc.)
- conditions (cold vs playbook vs stress)
- containers (local vs server)

---

## Required Logging (for comparability)

Record **every run**:
- model name + version (+ quant, if applicable)
- context length
- temperature, top_p, top_k, repetition penalty
- max tokens
- stop sequences
- retrieval on/off
- retrieval settings (top_k, chunk size, similarity threshold if available)
- exact system prompt version used
- date/time + run label

If sampling or retrieval settings change between runs, comparisons become unreliable.

---

## Safety + No-Exfil Expectations

This pack includes an Operator prompt that:
- forbids invention beyond Playbook text
- requires “Not found in playbook” for missing material
- requires Source Trace on every answer
- discourages bulk dumping of Playbook text (“no-exfil”)

Evaluators should treat the Playbook folder as **read-only** and avoid copying large verbatim excerpts into other systems.

---

## License / Use
Use the repository license as specified in `LICENSE`.

Recommended posture for a public evaluator pack:
- attribution required
- no derivatives if you want the text unchanged

(Your repo’s `NOTICE.md` defines scope and intent; keep it intact.)

---

## Contact / Provenance
Canonical author reference for this public pack:
- **Origin: Alyssa Solen**

For full canon and Origin-only materials, this public repo is intentionally incomplete by design.

