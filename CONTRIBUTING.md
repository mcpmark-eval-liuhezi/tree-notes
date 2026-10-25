# Contributing to tree-notes

Thanks for wanting to help — tree-notes is a small project, and we want contributing to be
easy and friendly. This guide covers the normal path: find something, claim it, change
something, open a pull request.

## Finding something to do

- Check the [issue tracker](https://github.com/mcpmark-eval-liuhezi/tree-notes/issues).
  The v0.1 backlog is nested under
  [Epic: tree-notes v0.1](https://github.com/mcpmark-eval-liuhezi/tree-notes/issues/1).
- If you find a bug or have an idea that isn't listed yet, open a new issue first so we
  can agree on the approach before you spend time on it.

## Getting started

1. [Fork](https://github.com/mcpmark-eval-liuhezi/tree-notes/fork) the repository and
   clone your fork.
2. Create a branch for your change:
   ```sh
   git switch -c my-change
   ```
3. Make your change. Keep the diff as small as it can honestly be.
4. If you're adding code, include a test that would fail without it. If you're adding
   docs, check the links actually resolve.

## Commit style

Write commit messages in the imperative ("Add", not "Added"): `Add tree list command`.
The first line should be able to finish the sentence "If applied, this commit will…".

## Pull requests

- Open pull requests against `main`.
- Use a short, imperative title.
- Reference the issue you're fixing in the description (e.g. "Closes #3") so the issue
  closes automatically on merge.
- Make sure CI is green before asking for a review.
- Don't be shy about opening a draft pull request early — feedback is cheaper before
  the code is finished.

## Reviews

Everyone's contributions get reviewed, including maintainers'. Reviews should be about
the change, never the person. If you disagree with review feedback, say so — a short
conversation beats a silent compromise.

## Questions

Ask in the issue itself, or open a new "question" issue. There are no stupid questions
here; there is only a tree of notes.
