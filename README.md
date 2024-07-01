# Git Commit with Log

1. Create a `~/logs` directory.

2. Add something like this to your `~/.bashrc`

```
# Log all git commits.
alias git="/path-to-repo/git-commit-with-log"
```

3. Run reports.
```
# Run report for the current month.
./git-commit-report

# Run report for July 2024.
./git-commit-report 202407
```

