# merge-conflict-project

A small, focused practice repository for deliberately creating and resolving Git merge conflicts.

## What this covers

**Deliberate Conflicts**
`conflict.txt` was modified differently on diverging branches (including a `staging` branch) to force a real merge conflict — not a fast-forward.

**Manual Resolution**
Conflicts were resolved by manually editing out the `<<<<<<<` / `=======` / `>>>>>>>` markers in `conflict.txt`, then completing the merge with `git add` and `git commit`.

**Pull Request Workflow**
The `staging` branch was merged back into `main` through a pull request on GitHub, practicing the same review-and-merge flow used in real team workflows.

## Why this exists

Merge conflicts are one of the parts of Git that only make sense after hitting them for real. This repo exists purely to practice recognizing, understanding, and resolving them without the pressure of a live project.
