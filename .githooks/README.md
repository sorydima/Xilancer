# Git Hooks

To enable these hooks locally:

```
git config core.hooksPath .githooks
```

Hooks included:

- `pre-commit`: runs formatting and analysis when available
- `commit-msg`: checks Conventional Commit style
