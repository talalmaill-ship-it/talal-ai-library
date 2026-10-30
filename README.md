# Talal AI Library

A personal, English-language library for task execution and guided learning. Internal audit is the first domain; the architecture supports additional domains without duplicating shared rules.

## Start here

1. Read [the operating rules](core/operating-rules.md).
2. Choose a task from [the catalog](catalog.json).
3. Give your model the operating rules **and** the selected task file. Repository access alone does not prove that a model read either file.
4. Select Execute, Guided, Learn, or Prompt. A clear task request starts Execute directly; an unclear request receives the four choices.
5. Run a matching test before accepting a revision.

## First three task prototypes

| ID | Task | File |
| --- | --- | --- |
| RPT-001 | Audit finding development | [Open](domains/audit/tasks/RPT-001.md) |
| PLAN-003 | Audit work program development | [Open](domains/audit/tasks/PLAN-003.md) |
| RPT-002 | Executive summary development | [Open](domains/audit/tasks/RPT-002.md) |

All three are **draft prototypes**, not validated releases. Existing IDs are preserved from SAR Audit Assistant. The installed plugin and its 44 templates have not been changed or fully imported here.

## Work with ChatGPT and Claude

- [Collaboration workflow](docs/collaboration.md): one author, one reviewer, shared files and explicit revisions.
- [Claude review prompt](handoffs/claude-review.md): paste this after connecting or uploading the files.
- [Agent instructions](AGENTS.md) and [Claude instructions](CLAUDE.md): entry points for coding tools. Web chats may require you to supply these instructions yourself.
- [Test pack](tests/audit/expired-certificates.md): synthetic competency-certification case and adversarial variations.
- [Review record](tests/review-record.md): honest distinction between structural review and model execution.

GitHub is the source of record. Neither chat's memory is a substitute for the files. Do not assume automatic synchronization, write access, or communication between models.

## Roadmap

1. Validate these three tasks against fixed cases in both models.
2. Revise and migrate the remaining audit templates in batches.
3. Add the next domain based on actual needs.
4. Create distribution packages for the SAR plugin and Claude; inspect and test each package before release.
5. Consider a multi-model interface after the content and evaluation process work reliably.

## Status

Foundation draft 0.1.0. English is the default for all library interactions and outputs. User overrides apply. No automatic model runner, plugin exporter, website, or live SAR connection is implemented.
