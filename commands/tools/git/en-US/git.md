+++
summary = "Quick reference for practical Git version-control commands."
+++
---

# Git command quick reference

Git tracks project changes, manages branches, and coordinates work with remote repositories. Each command has its own page:

```bash
lcmd git status
lcmd git add
lcmd git commit
lcmd git push
```

## Everyday work

- `status` — inspect working-tree and index changes
- `add` — stage changes
- `commit` — save a commit
- `diff` — review changes
- `log` — browse commit history
- `show` — inspect a commit
- `grep` — search tracked files

## Repositories and files

- `init` — create a repository
- `clone` — copy a remote repository
- `mv` — move or rename tracked files
- `rm` — remove files from tracking
- `archive` — export a revision
- `check-ignore` — inspect ignore rules
- `ls-files` — list indexed files

## Branches and commits

- `branch` — manage branches
- `switch` — switch branches
- `merge` — merge branches
- `rebase` — replay commits on a new base
- `cherry-pick` — apply selected commits
- `tag` — mark releases
- `worktree` — use multiple working directories

## Remote collaboration

- `remote` — manage remote URLs
- `fetch` — download remote updates
- `pull` — download and integrate updates
- `push` — publish local commits
- `ls-remote` — inspect remote refs

## Undo and recovery

- `restore` — restore files or unstage changes
- `reset` — move a branch pointer or reset the index
- `revert` — undo a commit with a new commit
- `reflog` — inspect reference history
- `stash` — temporarily save uncommitted changes
- `clean` — remove untracked files (use carefully)

## Troubleshooting and maintenance

- `blame` — find the last change to each line
- `bisect` — locate a bug-introducing commit
- `describe` — describe a revision relative to tags
- `fsck` — check repository integrity
- `gc` — clean and optimize repository data
- `count-objects` — inspect object storage usage
- `bugreport` — collect Git environment details
- `diagnose` — create a diagnostic archive

## Patches and other workflows

- `format-patch` — export commits as patches
- `am` — apply mailbox patches
- `request-pull` — prepare a pull request summary
- `bundle` — package repository history
- `submodule` — manage nested repositories
- `notes` — attach notes to commits
- `shortlog` — summarize commits by author
- `range-diff` — compare commit series

## Configuration and help

- `config` — manage Git settings
- `help` — open command help
- `difftool` — compare changes with an external tool
- `mergetool` — resolve conflicts with an external tool
- `checkout` — legacy branch switching and file restoration command

## Scope

This knowledge base focuses on Git commands with practical value. Options and examples are selected for quick reference rather than exhaustive coverage. For complete details, see the [official Git documentation](https://git-scm.com/docs).
