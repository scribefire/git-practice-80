# Git Practice

A small repository for keeping files created while practicing Git. It is a version-control exercise archive rather than a runnable application.

## Repository contents

The root currently contains a handful of numbered practice files:

- `practice2.txt`
- `practice3.txt`
- `practice9.txt`
- `practice11.txt`
- `practice13.txt`

Some files are blank in the current snapshot. The repository has no application dependencies or build step.

## Inspecting the history

Clone the repository and inspect the commits and branches with Git:

```bash
git clone https://github.com/scribefire/git-practice-80.git
cd git-practice-80
git log --oneline --all --decorate
git branch --all
```

Use `git show <commit>` or `git log -- <file>` to review how an individual practice file changed.
