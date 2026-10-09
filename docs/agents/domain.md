# Domain docs

## Layout

This repo uses a single-context layout:

- `GLOSSARY.md`: domain terms at the repo root.
- `docs/adr/`: architecture decision records.

## Before exploring

Read `GLOSSARY.md` and the ADRs relevant to the current task.

If these files are absent, proceed silently. The `domain-modeling`
skill creates them when terms or decisions are resolved.

## Use domain terms

Use the terms defined in `GLOSSARY.md` when naming domain concepts.
If a needed term is missing, reconsider the wording or note the gap
for `domain-modeling`.

## Surface decision conflicts

If a proposal contradicts an ADR, identify the ADR and explain why
the decision should be reconsidered.
