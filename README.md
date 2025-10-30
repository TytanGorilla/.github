# .github

Account wide accessible templates

## Workflows

- `changelog-required`: Blocks `feat:` and `fix:` pull requests that do not update the `[Unreleased]` section of `CHANGELOG.md`, reminding contributors to document user-facing work.

## Working with this repository

- **Open pull requests instead of pushing directly to `main`.** Branch-based review keeps history clean, requires approvals before changes propagate to every consumer of these shared workflows, and gives automation (like the changelog guard) a chance to run.
- **Use the pull request template.** `.github/pull_request_template.md` captures the checklist expected by the team—tests, documentation updates, changelog notes, and rollback guidance—so every change lands with the right context.
- **Link the relevant issue template entry.** Feature and chore issue forms describe the files to touch and changelog expectations, making it easier to validate that a PR met the agreed scope.
- **Squash-merge after approval.** Once reviewers sign off and checks are green, prefer the "Squash and merge" option so the shared history stays linear while still recording the branch discussion for posterity.
