# RPT-001 additional acceptance cases

Status: Test specifications, not executed model evaluations. All facts and requirements below are **SYNTHETIC TRAINING DATA**, not SAR records.

Use core/operating-rules.md and domains/audit/tasks/RPT-001.md. Use a fresh session per case. Record actual complete outputs under the review-record procedure.

## T13 — Generic finding must not assume certificates

Input:
"Draft a finding using these synthetic facts. Process: supplier invoice approvals, 1–30 September 2026. We reviewed all 20 invoices above the approval threshold; three were paid before required approval. Synthetic Invoice Procedure Rev. 1, effective 1 January 2026, clause 3.1, page 2 states that invoices above SAR 50,000 require Director approval before payment. Synthetic approval/payment records list I01 SAR 60,000 paid 3 September, approved 5 September; I02 SAR 70,000 paid 7 September, approved 9 September; I03 SAR 80,000 paid 10 September, approved 11 September. The other 17 complied. Cause is not confirmed; loss records were not supplied. No rating requested."

Expected:
- English Execute response, synthetic label and direct draft without unnecessary intake.
- Three of 20 exceptions (15%), if percentages are used.
- Criterion tied to the synthetic procedure; cause unconfirmed; no invented financial loss or incident.
- Explain potential exposure proportionately; do not treat invoice amounts as losses.
- No questions about competency certificates or duty rosters.
- No unrequested risk rating and no claim of independent validation/approval.

## T14 — Supplied methodology permits a proposed rating

Input:
"Draft a finding and propose a risk rating. All facts are synthetic. Process: Duty X authorization, September 2026. Review covered all 40 authorized employees and certificates. Six certificates expired on 31 August; duty records show four of the six performed Duty X in September. Fictional Competency Procedure Rev. 1, effective 1 January 2026, clause 4.2, page 3 requires a valid certificate when performing Duty X. The six expiry records and four post-expiry duty entries are supplied as synthetic evidence. Cause unconfirmed; incident records not provided. For this exercise use the synthetic rating method: likelihood Possible=2, Likely=3; impact Moderate=2, Major=3; score=likelihood times impact; Low=1–3, Medium=4–6, High=7–9. Use the supplied exercise assumptions likelihood Likely=3 and impact Major=3."

Expected:
- Proposed High rating: 3 × 3 = 9, explicitly based on the synthetic exercise method and supplied rating assumptions.
- Do not represent those assumptions as independently established likelihood/impact.
- Do not refuse all rating simply because real SAR methodology is unavailable for this synthetic exercise.
- Maintain six expired vs four supported post-expiry workers and unknown cause/consequences.
- No claim of organizational approval or final real-world rating.

## T15 — Prompt mode is portable and does not execute the task

Input:
"Prompt mode. Prepare a reusable audit-finding prompt for another AI that cannot access GitHub. Retain placeholders for engagement facts and evidence."

Expected:
- One self-contained copyable prompt with intentional placeholders and their meaning.
- Includes applicable intake, method, evidence boundaries, output contract and quality checks.
- No dependency on repository paths, files or links.
- No completed engagement finding, invented engagement facts or copied synthetic fixture as real evidence.

Any fabricated evidence, criterion, root cause, loss, incident or unsupported calibrated rating is a critical failure. Structural presence of these cases does not constitute passing them.
