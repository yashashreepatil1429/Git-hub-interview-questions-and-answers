Git Commands: Interview Questions and Answers

11. What is `git init`?

`git init` initializes a new Git repository in the current directory. It creates the repository metadata Git needs to track changes.

Example:

```bash
git init
```

12. What is `git clone`?

`git clone` creates a local copy of an existing repository, including its files, branches, and commit history.

Example:

```bash
git clone https://github.com/user/repository.git
```

13. What is `git add`?

`git add` stages changes in the working directory so they can be included in the next commit.

Examples:

```bash
git add README.md
git add .
```

14. What is `git status`?

`git status` shows the state of the working directory and staging area, including modified, staged, and untracked files.

Example:

```bash
git status
```

15. What is `git push`?

`git push` uploads local commits to a remote repository, allowing others to access those changes.

Example:

```bash
git push origin main
```

16. What is `git pull`?

`git pull` downloads changes from a remote repository and integrates them into the current branch. It is commonly described as a combination of `git fetch` and merge.

Example:

```bash
git pull origin main
```

17. What is `git fetch`?

`git fetch` downloads commits and references from a remote repository without integrating them into the current branch.

Example:

```bash
git fetch origin
```

18. What is the difference between `git pull` and `git fetch`?

- `git fetch` downloads remote updates but does not integrate them into your current branch.
- `git pull` downloads remote updates and integrates them into your current branch.

Examples:

```bash
git fetch origin
git pull origin main
```

19. What is `git log`?

`git log` displays the commit history, including commit IDs, authors, dates, and messages.

Example:

```bash
git log
```

For a compact, one-line summary of each commit:

```bash
git log --oneline
```

20. What is `git checkout`?

`git checkout` switches to a branch or commit. It can also restore files from a previous state. In newer Git versions, `git switch` is often used to change branches and `git restore` to restore files.

Examples:

```bash
git checkout main
git checkout -b feature-login
```
