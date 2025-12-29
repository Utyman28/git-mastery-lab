# Git Mastery Lab

This repository demonstrates **production-grade Git workflows** commonly used in **Cloud & DevOps teams**.

It focuses on **safe collaboration, clean history, and recovery techniques** rather than basic Git commands.
This repository demonstrates production-grade Git workflows for Cloud & DevOps engineers.

## What this repo proves
- Atomic commits via interactive staging (`git add -p`)
- Rebase + conflict resolution
- Safe rollback on shared history (`git revert`)
- Recovery using reflog
- Regression debugging using git bisect
- Versioning with tags + changelog

## Contributing
- Use feature branches
- Keep commits atomic

## Running tests
```bash
python -m pytest

## How to review this repository

To understand the workflows demonstrated here:
- Review the commit history using `git log --oneline --graph`
- Inspect the rebase and recovery steps via `git reflog`
- Review the feature branch PR history


