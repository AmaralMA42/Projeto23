# SYNC DELTA — EDUARDO ONBOARDING LAYER

**Date:** 2026-09-25  
**From:** Marco/IA  
**To:** Eduardo/IA  
**Baseline:** repository bootstrap through commit d022ece59f5045cd6e209b019b529d7b9c89a97e  
**Scope:** shared / onboarding  
**Status:** ACCEPTED_OPERATIONAL_HANDOFF

## NEW EVIDENCE

None. No scientific evidence changed.

## RESULTS

A human-first onboarding layer was added for Eduardo:

- `EDUARDO_START_HERE.md`
- `prompts/EDUARDO_AI_START_PROMPT.md`
- `sync/EDUARDO_FLOW_GUIDE.md`

The repository README now routes a new user to these surfaces first.

The proactive autoboot now explicitly requires the AI to:

- explain scientific function before internal terminology;
- translate internal statuses into plain language;
- explain what it can do with articles, data, ideas and results;
- recover project structure itself instead of asking the user to navigate files;
- explain the information flow briefly when relevant;
- proactively identify whether new material changes the project and whether a sync is needed.

## INTERPRETATION CHANGE

None scientifically.

Operational interpretation:

> the AI interface should hide most of the project machinery from the human user while preserving rigor underneath.

## HUMAN DECISIONS

Marco explicitly requested that Eduardo's lower familiarity with deep AI workflows be accommodated through brief, proactive explanations of capabilities and information flow.

## OPEN GATES

Scientific gates are unchanged.

ZA-M0 remains pre-compute.  
ZG remains an independent replication baseline.

## NEXT SAFE STEP

Eduardo can initialize his first AI session using `prompts/EDUARDO_AI_START_PROMPT.md` and then interact in natural language.

## ARTIFACTS

- `EDUARDO_START_HERE.md`
- `prompts/EDUARDO_AI_START_PROMPT.md`
- `sync/EDUARDO_FLOW_GUIDE.md`
- updated `README.md`
- updated `autoboot/PROACTIVE_BOOT.md`
