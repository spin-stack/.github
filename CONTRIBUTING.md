# Contributing

These rules apply to every Spinbox repository. Build and test steps live in each repository's
own README and AGENTS.md.

- **Open an issue before a large change.** Agreeing on the design first saves rewriting the code.
- **One pull request per feature.** No stacked sub-PRs; a feature is reviewed and merged whole.
- **Link the issue.** The PR description says `Closes #N` so the issue closes on merge.
- **Checks must be green.** A PR merges only after every required check passes.
- **Pull requests are rebase-merged, never squashed.** Each commit lands on `main` as written, so
  keep commits meaningful and their messages clear.
- **Security issues** go through private reporting, not public issues: see [SECURITY.md](SECURITY.md).
