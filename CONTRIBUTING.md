# Contribution Guide

Really glad you're interested in contributing. Please take a moment to read this note to better participate in making contributions.

## Reporting Issues

- Ensure the bug was not already reported by searching on GitHub under Issues.
- If you're unable to find an open issue addressing the problem, open a new one. Be sure to include:
  - A title and clear description.
  - As much relevant information as possible.
  - A code sample or an executable test case.

## Repository Setup

If you want to contribute to the project, you'll need to set up the repository on your local machine.

- Use [the latest LTS](https://nodejs.org/en/about/releases/) of [Node.js](https://nodejs.org/en/).
- Use [`pnpm`](https://pnpm.io/).

## Pull Requests

### Discuss first

Before you start to work on a feature pull request, it's always better to open a feature request issue first to discuss with the maintainers whether the feature is desired and the design of those features. This would help save time for both the maintainers and the contributors and help features to be shipped faster.

### Commit Convention

We use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, which allows the changelog to be auto-generated based on the commits. Please read the guide through if you aren't familiar with it already. There's some additional tips:

- Only `fix:` and `feat:` will be presented in the changelog.
- Note that `fix:` and `feat:` are for **actual code changes** (that might affect logic).
  For typo or document changes, use `docs:` or `chore:` instead:

  ~~`fix: typo`~~ -> `docs: fix typo`