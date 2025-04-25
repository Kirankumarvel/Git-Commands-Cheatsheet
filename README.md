# 🚀 Git Commands Cheatsheet

A complete reference of daily-use Git commands every developer should know. This repository is helpful for beginners and seasoned Git users who want a quick reminder of the most used commands.

---

## 📋 Table of Common Git Commands

| **Command**               | **Usage**                                      | **Description**                                                                 |
|---------------------------|-----------------------------------------------|---------------------------------------------------------------------------------|
| `git init`               | `git init [directory]`                         | Initializes a new Git repository.                                              |
| `git clone`              | `git clone <repository-url>`                  | Clones a remote repository to your local machine.                             |
| `git add`                | `git add <file(s)>`                            | Adds file(s) to the staging area.                                              |
| `git commit`             | `git commit -m "<message>"`                   | Commits staged changes with a message.                                         |
| `git push`               | `git push <remote> <branch>`                  | Pushes local commits to the remote branch.                                     |
| `git pull`               | `git pull <remote> <branch>`                  | Fetches and merges changes from a remote branch.                               |
| `git fetch`              | `git fetch <remote>`                           | Fetches changes from a remote without merging.                                 |
| `git status`             | `git status`                                   | Shows the current status of the working directory and staging area.            |
| `git branch`             | `git branch`                                   | Lists all local branches.                                                      |
| `git checkout`           | `git checkout <branch>`                        | Switches to the specified branch.                                              |
| `git merge`              | `git merge <branch>`                           | Merges a branch into the current branch.                                       |
| `git log`                | `git log`                                      | Displays commit history.                                                       |
| `git diff`               | `git diff`                                     | Shows differences not yet staged or committed.                                 |
| `git reset`              | `git reset <file(s)>`                          | Unstages files without changing content.                                       |
| `git remote`             | `git remote -v`                                | Lists remote repositories and their URLs.                                      |
| `git stash`              | `git stash`                                    | Temporarily stashes uncommitted changes.                                       |
| `git rebase`             | `git rebase <branch>`                          | Reapplies commits onto another base branch.                                    |
| `git tag`                | `git tag <tag-name>`                           | Tags the current commit.                                                       |
| `git checkout -b`        | `git checkout -b <new-branch>`                 | Creates and checks out a new branch.                                           |
| `git remote add`         | `git remote add <name> <repository-url>`       | Adds a new remote repository.                                                  |

---

## 🚀 Advanced Git Commands Cheatsheet

| **Command**              | **Usage**                                      | **Description**                                                                 |
|--------------------------|-----------------------------------------------|---------------------------------------------------------------------------------|
| `git log --oneline`      | `git log --oneline`                           | Displays a compact log with commit hash and message in one line.               |
| `git log -p -1`          | `git log -p -1`                               | Shows the patch (code diff) of the last commit.                                 |
| `git show`               | `git show <commit-id>`                        | Displays detailed info about a specific commit.                                 |
| `git diff --staged`      | `git diff --staged`                           | Shows the differences between staged changes and the last commit.              |
| `git restore`            | `git restore <file>`                          | Restores file content to the last committed state.                              |
| `git clean`              | `git clean -f`                                | Removes untracked files from the working directory.                             |
| `git cherry-pick`        | `git cherry-pick <commit-id>`                 | Applies a specific commit from one branch onto another.                         |
| `git revert`             | `git revert <commit-id>`                      | Creates a new commit that undoes the changes made by a previous commit.         |
| `git rebase -i`          | `git rebase -i HEAD~n`                        | Interactive rebase to edit, reorder, squash, or drop commits.                   |
| `git blame`              | `git blame <file>`                            | Shows line-by-line revision history for a file.                                 |
| `git shortlog`           | `git shortlog`                                | Summarizes commit history by author.                                            |
| `git archive`            | `git archive --format=zip --output=foo.zip master` | Creates an archive of files from a given tree (e.g., master branch).           |
| `git config`             | `git config --global user.name "Your Name"`    | Sets user-level Git configuration.                                              |
| `git reflog`             | `git reflog`                                  | Shows the history of HEAD and branch movements (even after reset).              |
| `git tag -a`             | `git tag -a v1.0 -m "Version 1.0"`            | Creates an annotated tag with a message.                                        |
| `git push --tags`        | `git push --tags`                             | Pushes all local tags to the remote.                                            |
| `git bisect`             | `git bisect start / git bisect bad / git bisect good` | Used to find the commit that introduced a bug.                                 |
| `git submodule`          | `git submodule add <repo-url>`                | Adds a Git repository as a subdirectory (submodule) of another.                 |
| `git switch`             | `git switch <branch-name>`                    | Modern alternative to `git checkout` for switching branches.                    |

---

## 📚 How to Use

1. **Clone this repository** to have a quick cheat sheet for Git commands:
   ```bash
   git clone https://github.com/Kirankumarvel/Git-Commands-Cheatsheet.git
   ```
2. Open the `README.md` or refer to this file for common and advanced Git commands.
3. Practice these commands in your own Git repositories or while working on projects.

---

## 🙌 Contributing

Contributions are welcome! If you think any commonly used Git commands are missing, feel free to open an issue or submit a pull request.

---

## 📜 License

This repository is licensed under the MIT License. Feel free to use and share it!
