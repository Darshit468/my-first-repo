# My First Repository — Learning Log

A public log of me learning Git and GitHub, one commit at a time. This is not a showcase project — it's the practice ground where I build the habits I'll use for real work later.

**Started:** 15 November 2026
**Goal:** get comfortable with the everyday Git workflow — commit, push, branch, pull request — before I start putting real projects on GitHub.

## About me

B.Tech AI & ML student at Christ University, working in Python, C/C++ and machine learning. Those projects get their own repositories once they're worth reading; this one exists so I can make mistakes safely.

## Log

### 2026-11-15 — Day one

- Created this repository on GitHub (`Darshit468/my-first-repo`), default branch `main`.
- First commit: this README and a `.gitignore`.
- Learned that `git init` creates a local repo, `git remote add origin <url>` points it at GitHub, and `git push -u origin main` publishes — the `-u` means later pushes only need `git push`.
- Realised the first version of this README was committed before it said anything worth reading, so I'm rewriting it as a log instead of a placeholder.

## What I'm working towards

- [ ] Commit something every week, even something small
- [ ] Create a branch, push it, and open a pull request
- [ ] Resolve a merge conflict on purpose, so the first real one isn't frightening
- [ ] Get fluent in `git log`, `git diff` and `git restore`
- [ ] Put a finished project on GitHub and pin it

## Commands I've actually used

```bash
git status                  # what has changed
git add -A                  # stage everything
git commit -m "message"     # save a snapshot
git push                    # send commits to GitHub
git log --oneline           # compact history
```

## Notes to self

- `.gitignore` is here so `.env` files, virtual environments and `node_modules` never get committed by accident — secrets in a repo are permanent and public.
- Commit messages should say *why* something changed, not just what changed.
- A repo with no code in it is fine to learn with, but it is not portfolio material. Don't confuse the two.
