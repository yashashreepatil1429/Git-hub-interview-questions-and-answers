Git Hub Interview Questions and Answers

1. Git Fundamentals

1. What is Git?

Git is a free, open-source, distributed version control system used to track changes in source code during software development.

It helps developers:

- Track code changes.
- Maintain different versions of a project.
- Work with multiple developers.
- Restore previous versions.
- Manage code efficiently.

Example: If you accidentally delete some code, Git helps you recover the previous version.

2. What is GitHub?

GitHub is a cloud-based platform used to host Git repositories and collaborate with other developers.

It provides features like:

- Repository management.
- Pull requests.
- Issues and project tracking.
- Code reviews.
- Team collaboration.

3. What is the difference between Git and GitHub?

| Git | GitHub |
| --- | --- |
| Version control system | Code hosting platform |
| Works locally | Works online |
| Tracks code changes | Hosts Git repositories |
| Developed by Linus Torvalds | Owned by Microsoft |
| Command-line tool | Web-based platform with Git integration |

4. What is a Version Control System (VCS)?

A Version Control System is a tool that tracks and manages changes made to files over time.

Types:

- Local Version Control System.
- Centralized Version Control System (CVCS).
- Distributed Version Control System (DVCS).

Git is a Distributed Version Control System.

5. What is a repository in Git?

A repository (repo) is a storage location where project files and their version history are maintained.

Types:

- Local repository – stored on your computer.
- Remote repository – stored on platforms like GitHub.

Example: A React project stored in a GitHub repository.

6. What is the difference between local and remote repositories?

- Local repository: Exists on your computer and allows you to track changes.
- Remote repository: Exists on a server such as GitHub and allows developers to share code.

7. What is a commit in Git?

A commit is a snapshot of changes made to a project at a particular point in time. It helps developers track project history.

Command:

```bash
git commit -m "Added login functionality"
```

8. What is a branch in Git?

A branch is an independent line of development that allows developers to work on new features without affecting the main code.

Examples:

- `main` – production-ready code.
- `feature-login` – login functionality.
- `feature-payment` – payment functionality.

Command:

```bash
git branch feature-login
```

9. What is the difference between Git merge and Git rebase?

| Git Merge | Git Rebase |
| --- | --- |
| Combines branches | Moves commits onto another base |
| Preserves branch history | Rewrites commit history |
| Can create a merge commit | Usually creates a linear history |
| Suitable for preserving collaboration history | Useful for cleaning up local history |

10. What is a merge conflict?

A merge conflict occurs when Git cannot automatically combine changes from different branches, usually because the same part of a file has been modified.

How to resolve:

1. Open the conflicted file.
2. Identify the conflicting changes.
3. Edit and keep the correct code.
4. Remove conflict markers.
5. Add and commit the resolved file.
