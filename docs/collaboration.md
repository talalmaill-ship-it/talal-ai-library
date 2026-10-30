# ChatGPT–Claude collaboration

## Source of record

Use this private repository, an explicit branch and a known commit when available. A model must state which files it actually read. If access fails, upload those files manually. Refresh connected repository content when it changes; do not assume live synchronization.

## Author/reviewer cycle

1. Choose one task and assign one model to author the change.
2. Give it the current shared rules, task file, tests and relevant constraints.
3. Save a focused change on a branch or as a clearly labeled patch. Preserve unrelated files.
4. Give the other model the same source revision, changed files and tests. Use handoffs/claude-review.md when Claude reviews.
5. Review objections for evidence and practical impact, not agreement between models.
6. Run fixed cases with exact inputs in both models; save actual outputs and test results.
7. Reconcile changes, rerun affected cases and accept a version after critical failures are resolved.

Do not let both models edit the same branch/files simultaneously. A reviewer may propose a patch; that does not authorize deployment of an installed plugin.

## Handoff information

Include: branch/commit; objective; files read/changed; preserved requirements; checks actually run; observed failures; remaining work; next action. Never claim automatic communication between chats.

## Using the library

For a chat, provide core/operating-rules.md plus a selected task file. CLAUDE.md and AGENTS.md are tool entry points, not guaranteed automatic context in every web interface. Prompt mode must return a self-contained prompt, including the necessary rules; it must not merely tell the recipient to open inaccessible repository paths.

## Later distribution

The 44-template plugin remains a separate installed artifact. Before migration, retrieve its current release, preserve identity and unrelated content, reconcile conflicting template guidance and inspect the packaged output. Library commits do not automatically update the plugin. No exporter or multi-model runner is implemented yet.
