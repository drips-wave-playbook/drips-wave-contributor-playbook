# Submitting Pull Requests

Your PR is how your work gets evaluated and merged. This guide covers the technical and social aspects of submitting a strong pull request.

## Before You Submit

### Verify Assignment

- [ ] You are **officially assigned** to the issue
- [ ] You understand the **acceptance criteria**
- [ ] You've completed the work locally

### Run a Self-Review

- [ ] Changes match the issue scope (no unrelated edits)
- [ ] No broken links or syntax errors
- [ ] Markdown renders correctly (check in a preview)
- [ ] Commit messages are clear

## Branching Strategy

Use descriptive branch names:

```bash
# Good
git checkout -b docs/add-wallet-setup
git checkout -b fix/typo-getting-started
git checkout -b feat/glossary-section

# Bad
git checkout -b patch-1
git checkout -b my-changes
