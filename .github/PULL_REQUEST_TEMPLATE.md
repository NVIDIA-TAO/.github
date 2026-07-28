<!--
Thanks for sending a pull request!

Please write the PR title to summarize what this PR proposes — it becomes the
changelog entry and the squashed commit subject. Prefix with the change type,
e.g. "fix(cli): reject empty annotation records".

Fill in every section below. A reviewer should be able to understand what
changed and why, and trust that it works, without reading the diff first.
Keep the description updated as the PR evolves.

If the PR is unfinished, open it as a Draft, or prefix the title with [WIP].
Do NOT use a pull request to report a security vulnerability — see SECURITY.md.
-->

### What changes are proposed in this pull request?

<!--
Outline what you changed and how it addresses the problem. Notes that make review
faster belong here: a class or module layout if you restructured something, a link
to a design document or issue discussion, references to how other projects solve
the same problem.

If this adds or changes a user-facing capability, include a short usage example:

  ```python
  # how someone uses this
  ```
-->

### Why are the changes needed?

<!--
The motivation, not the mechanics. If you fix a bug, explain why the old behavior
was wrong. If you add an API, explain the use case it unblocks. Summarize this
even when it lives in an issue — reviewers should not need another tab.
-->

### Related issues

<!--
"Fixes #123" / "Closes #123" to auto-close on merge, or "Part of #456".
Write "N/A" if there is no associated issue. Substantial changes should have an
issue discussing the approach before the code is written.
-->

### Does this PR introduce _any_ user-facing change?

<!--
This means *any* change a user could notice: new features, bug fixes, changed
output, renamed flags, different defaults, altered error messages, schema or API
changes. Documentation-only updates are not user-facing.

If yes: describe the previous behavior and the new behavior, and show the
difference — console output before and after is ideal. Call out explicitly
whether it breaks existing usage, and what users must do to migrate.

If no, write "No".
-->

### How was this patch tested?

<!--
Be specific: the commands you ran, the tests you added, and any manual
verification. "CI is green" is not a test plan for a behavior change.
Cover the negative cases too, not just the happy path.
If you did not add tests, say why it was difficult or unnecessary.

  $ <test command>
-->

<!-- Paste the relevant output: test summary, before/after comparison, or
     benchmark numbers. Redact tokens, credentials, and private paths. -->

### Was this patch authored or co-authored using generative AI tooling?

<!--
Generative AI tooling is allowed, and you remain fully responsible for what you
submit: you must understand every line, have run it, and be able to answer review
questions about it. PRs the author cannot explain will be closed.

If AI tooling was used, include the line below with the tool name and version.
If no, write "No".

Generated-by: <tool name and version>
-->

### Release note

<!--
One sentence, written for a user reading the changelog — not for a reviewer
reading the diff. Write "NONE" if this change is invisible to users.

Good:  Fixed a crash when converting datasets containing empty annotation records.
Bad:   Refactored the converter and fixed a bug.
-->

```release-note

```

### Checklist

- [ ] My commits are signed off per the DCO (`git commit -s`) — see `CONTRIBUTING.md`
- [ ] I have read the contributing guidelines
- [ ] The code follows the project's style, and lint and format checks pass locally
- [ ] I added or updated tests covering this change
- [ ] All tests pass locally
- [ ] I added or updated documentation (README, docstrings, docs pages, examples)
- [ ] I updated the version, changelog, or migration notes if this change requires it
- [ ] If this touches components that are optional to install, the imports are guarded
      so the package still works without them (reviewers: please verify this)
- [ ] No secrets, credentials, proprietary data, or customer data are included in this PR
- [ ] I understand this contribution is licensed under the repository's license, and that
      my commit author name and email become permanently public once merged

### Notes for reviewers

<!--
Anything that makes review faster: where to start, decisions you were unsure
about, areas you want scrutinized, or follow-up work deliberately left out.
Reviewers are volunteers on other schedules — if you see no response after a few
days, a polite ping on this PR is welcome.
-->
