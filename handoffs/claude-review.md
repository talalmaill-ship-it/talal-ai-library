# Ready-to-paste Claude review prompt

Review and improve the first draft of my English-language AI task library. This is a repository development task, not a request to execute an audit finding or to rewrite this request.

## Outcome

Return a focused review and concrete revisions that make the library reliably useful for execution and learning, from beginners through Directors and VPs. Start with RPT-001; do not expand to all 44 templates or build a website.

## Inputs

Repository: https://github.com/talalmaill-ship-it/talal-ai-library
Read README.md, AGENTS.md, core/operating-rules.md, domains/audit/tasks/RPT-001.md, tests/audit/expired-certificates.md, tests/review-record.md and docs/collaboration.md. Read the other two task files only to check shared-rule consistency. Identify the branch/commit if accessible. If files cannot be read, request the exact missing files rather than pretending to inspect them.

## Preserved requirements

- English default.
- Four modes: Execute, Guided, Learn, Prompt.
- Explicit execution requests start Execute; ambiguous openings offer four choices.
- Ask only material unanswered questions, at most three focused groups per round.
- Produce useful work with labeled evidence gaps; no endless intake.
- Adapt explanations and outputs to the user/audience without weakening evidence requirements.
- Preserve task IDs and distinguish real evidence, user assertions and synthetic examples.
- Do not fabricate criteria, counts, root causes, incidents, ratings or approvals.
- Do not change the installed plugin or publish anything as a side effect.

## Review method

Check routing, intake burden, evidence sufficiency, date applicability, output clarity, teaching usefulness and conflicts across shared/task rules. Trace concerns to exact files/sections and show a concrete failure example. Distinguish definite defects from preferences. Do not claim an IIA requirement without an applicable authoritative source; this task does not require new standards research.

First review the text. Then, if the environment supports a clean test session with the stated context, run the test pack and preserve actual outputs. If not, label any walkthrough "predicted behavior"; it is not an executed test. Never mark unrun cases passed.

## Return

1. Concise assessment with the most consequential defects first.
2. Findings table: file/section, defect, concrete consequence, proposed correction.
3. Complete replacement text for changed files, or a patch if repository editing is available; keep unrelated content intact.
4. Checks actually run, observed outputs/failures and untested cases.
5. Handoff: source revision, changed files, remaining work and next action.

Before returning, verify source fidelity, requirement coverage and whether every claimed test really ran. Give concise reasons for material decisions, not hidden chain-of-thought.
