# tree-notes

**tree-notes** is a small terminal notebook that keeps your notes in a tree.

Every note is a plain-text file. Every branch of the tree is a directory. There is no
database, no lock-in, and no format you cannot read with `cat`, edit with `vim`, or
sync with `git`.

## Why

Most note tools make you adapt to them: proprietary databases, opaque export formats,
ideas trapped inside one app. tree-notes takes the opposite position — the filesystem is
already a perfectly good tree, so the tool should stay out of the way and just be the
convenient front door to it.

The goal for v0.1 is deliberately small: create a note, and look at the tree.

```text
$ tree-notes add "Zettelkasten ideas"
$ tree-notes tree
reading/
  2025-01-08 how to take smart notes
projects/
  tree-notes/
    zettelkasten ideas
``` 

## Prior art

We did a real search across GitHub for existing note-taking / notebook CLI projects
(several phrasings: "note-taking cli", "terminal notes plain text", "command line
notebook app") before writing this down. These repositories genuinely appeared in
those results:

- [zk-org/zk](https://github.com/zk-org/zk) — a plain-text note-taking assistant written
  in Go, focused on Zettelkasten-style workflows. The closest thing to a "mature"
  reference point in this space, and a good study in what a note CLI looks like once it
  grows editing, filtering and notebook-management commands.
- [rhysd/notes-cli](https://github.com/rhysd/notes-cli) — a small markdown note-taking
  CLI app designed to play nicely with your favourite editor and other CLI tools, which
  is the same "stay a friendly front door to plain files" philosophy tree-notes wants.
- [atbuy/noteui](https://github.com/atbuy/noteui) — a terminal note-taking app for
  browsing, searching, previewing and organising plain-text notes stored as regular
  files; useful inspiration for how a tree of notes can be presented interactively in a
  TUI.
- [HalCanary/notebook](https://github.com/HalCanary/notebook) — a command-line
  note-keeping app that uses Git for backups, an early and encouragingly minimal example
  of treating notes as just files under version control.

## Status

Pre-v0.1. No code yet — see [docs/ROADMAP.md](docs/ROADMAP.md) for the v0.1 milestone
and the [issue tracker](https://github.com/mcpmark-eval-liuhezi/tree-notes/issues) for the
backlog.

## License

TBD
