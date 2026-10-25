# tree-notes roadmap

This is the working plan. v0.1 is intentionally tiny — one command that writes a note,
one command that shows the tree, and a written format so we stop guessing.

## v0.1 — "it exists"

The v0.1 milestone is the smallest version of tree-notes that is genuinely usable by
someone who is not one of its authors.

| # | Goal | Done means |
|---|------|------------|
| 1 | Define the note file format | A short written spec (location, naming, front-matter or the deliberate absence of it) that the other tasks can be built against. |
| 2 | Implement the `add` command | `tree-notes add "some title"` creates a note file in the right place in the tree and prints where it put it. |
| 3 | Implement the `tree` list command | `tree-notes tree` prints the whole tree of notes in an indented, readable form. |
| 4 | Write the getting-started guide | A new contributor can clone, build and make their first note in under five minutes without asking anyone. |

### Non-goals for v0.1

No search, no editing, no sync, no tags, no TUI. Those are v0.2+ material and deliberately
out of scope so the four goals above can land quickly.

## After v0.1 (rough ideas, no promises)

- `tree-notes open` — jump into a note in `$EDITOR`.
- Full-text search across the tree.
- Optional git integration for history and sync.
- Interactive tree browser in the terminal.
