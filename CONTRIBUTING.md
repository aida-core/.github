# Contributing to AIDA

Thanks for your interest in contributing. This guide is the org-wide default — individual repos may add their own `CONTRIBUTING.md` with project-specific details, which take precedence.

## Where to start

- **Bug reports & feature requests** — file an issue on the relevant plugin's repo, not on the org-level repos. The plugin map lives on the [org profile](https://github.com/aida-core).
- **Security issues** — please follow [SECURITY.md](SECURITY.md) instead of filing a public issue.
- **Just need help?** — see [SUPPORT.md](SUPPORT.md).

## Pull requests

1. **Open or claim an issue first** for anything beyond a typo or trivial fix. This avoids duplicate work and lets us flag scope concerns early.
2. **Fork and branch.** Branch names are conventional: `feat/<topic>`, `fix/<topic>`, `chore/<topic>`, `docs/<topic>`.
3. **Make your change.** Match existing style; don't bundle unrelated edits.
4. **Keep PRs focused.** One concern per PR. A 50-line PR gets reviewed in an hour; a 2,000-line PR gets reviewed next week.
5. **Update the changelog.** Most plugin repos enforce a `CHANGELOG.md` entry under `[Unreleased]`. Apply the `skip-changelog` label only for genuinely changelog-irrelevant PRs (typo fixes, internal CI tweaks).
6. **Open the PR against `main`.** Fill in the PR template; check the boxes you actually verified.

## Commit conventions

- We use **[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)** — `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, `test:`, `ci:`, `build:`.
- One logical change per commit. Squash-on-merge is the default, so commit history within a PR is mostly for the reviewer's benefit.
- **Do not include "AI co-author" trailers** (e.g., `Co-Authored-By: <some AI assistant>`). Tooling assistance is welcome and expected; attributing authorship to an AI tool is not. Authorship belongs to the human who exercised judgment, took responsibility, and owns the code. CI on most repos enforces this.

## Code review

- Reviewers respond within a few days for active repos; ping if a PR has been idle longer than a week.
- Address review comments either by making changes or replying with reasoning — don't silently ignore them.
- Approval from one maintainer is the bar for most repos; security-sensitive areas may require two.

## Testing & CI

Run the project's own tests and linters locally before opening a PR. CI must be green before merge. If CI fails for reasons unrelated to your change, flag it in the PR rather than retrying blindly.

## Licensing

By contributing, you agree that your contribution is licensed under the same license as the repo (typically MPL-2.0 — see the repo's `LICENSE`).

## Code of Conduct

Participation is governed by the org [Code of Conduct](CODE_OF_CONDUCT.md). Be the kind of person you want to collaborate with.
