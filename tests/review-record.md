# Review record

## Foundation 0.1.0

- Status: Draft, pending model execution and independent review.
- Completed: author review of requirement coverage, catalog paths, four-mode consistency, task output contracts and synthetic case arithmetic (6/40 = 15%; 4/40 = 10%).
- Not completed: live execution of T01–T12 in either model, independent Claude review, acceptance cases for PLAN-003 and RPT-002, installed plugin behavior verification.
- Release blockers: missing behavioral evaluation records; missing task-specific cases for two prototypes.
- Installed SAR Audit Assistant: unchanged.

## Record each subsequent run

- Date and model/version:
- Repository branch and commit:
- Task/test ID:
- Exact input and provided files:
- Complete output location:
- Applicable criteria:
- Pass/fail with observable evidence:
- Critical failures:
- Proposed changes and retest results:

Do not overwrite failed runs with successful ones; preserve the evidence trail. Do not call author predictions or checklist inspection a model test.

## Claude report received 30 October 2026 — pre-patch revision

- Source revision: a757a63fcafa245016e96ce421139f5c19896fa0, main.
- Source: review text pasted by the owner; disposition in docs/reviews/2026-10-30-claude.md.
- Reported tests: T01, T05 and T10 passed according to Claude; full raw outputs and exact model/version were not supplied.
- Limitation: T01 reportedly referenced stored user context; isolation was imperfect.
- Verification status: reported results only, not independently reproduced or accepted as auditable passes.
- Clean T02 and T03/T04/T06–T09/T11/T12 remain unverified; T05 is not a substitute for T02.

## Patch after Claude review — 30 October 2026

- Changed RPT-001: portable Prompt mode, explicit applicable-version request, bounded rating trigger, defined evidence-supported status and generic finding logic.
- Clarified T03/T04 inputs and expectations; added T13–T15 specifications for generalization, supported rating and Prompt portability.
- Checks: author text review and structural assertions over changed content. No fresh behavioral model execution performed in this session.
- Status: draft; post-patch T01–T15 outputs required. PLAN-003 and RPT-002 still need task-specific acceptance cases.
- Installed SAR Audit Assistant: unchanged.
