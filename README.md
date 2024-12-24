# Git Cheat Sheet

This is the A to Z Git command cheat sheet.

This repository provides a comprehensive Git cheat sheet for quick reference and learning. It covers common Git commands, workflows, and best practices.


## Sections
- [Configuration](Configuration.md)
- [Basic Workflow](Workflow.md)
- [Branching](Branching.md)
- [Stashing](Stashing.md)
- [Tagging](Tagging.md)
- [Undoing Changes](UndoingChanges.md)
- [Advanced Workflow](AdvancedWorkflow.md)
- [Tips and Tricks](TipsAndTricks.md)
- [Resources](Resources.md)




  ## Git Resources

- **Git**
  - [Resource 1](Tools/git_1.pdf)
  - [Resource 2](Tools/git_2.pdf)
  - [Resource 3](Tools/git_3.pdf)
  - [Resource 4](Tools/git_4.pdf)
  - [Resource 5](Tools/git_5.pdf)

---

## Contributions
Feel free to contribute by submitting a pull request!

# Configuration

### Setting Up Git
- **Set user name:** `git config --global user.name "Your Name"`
- **Set email:** `git config --global user.email "youremail@example.com"`
- **Check settings:** `git config --list`
- **Set default editor:** `git config --global core.editor nano`
- **Set merge tool:** `git config --global merge.tool vimdiff`
- **Set diff tool:** `git config --global diff.tool meld`

### Repository Setup
- **Create new repository:** `git init`
- **Clone a repository:** `git clone <repo-url>`
- **Add a remote repository:** `git remote add <name> <repo-url>`
- **List remote repositories:** `git remote -v`

# Basic Workflow

### Common Commands
- **Check status:** `git status`
- **Add changes to staging area:** `git add <file>`
- **Commit changes:** `git commit -m "Commit message"`
- **Push changes:** `git push`
- **Pull changes:** `git pull`
- **Fetch changes:** `git fetch`


# Branching

### Common Commands
- **Create a new branch:** `git branch <branch-name>`
- **Switch to branch:** `git checkout <branch-name>`
- **Create and switch to branch:** `git checkout -b <branch-name>`
- **List branches:** `git branch`
- **Merge branch into current branch:** `git merge <branch-name>`
- **Delete branch:** `git branch -d <branch-name>`
- **Force delete branch:** `git branch -D <branch-name>`


# Stashing

### Overview
Stashing allows you to save changes in your working directory temporarily without committing them. This is useful when you need to switch branches or work on something else but want to save your progress.

---

### Common Commands
- **Save changes to stash:** `git stash save "Message"`
- **List all stashes:** `git stash list`
- **Apply the latest stash:** `git stash apply`
- **Apply a specific stash:** `git stash apply stash@{<index>}`
- **Delete the latest stash:** `git stash drop`
- **Delete a specific stash:** `git stash drop stash@{<index>}`
- **Pop (apply and remove) the latest stash:** `git stash pop`
- **Create a stash and include untracked files:** `git stash -u`


# Resources

- [Official Git Website](https://git-scm.com/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials)
- [Git Immersion](https://gitimmersion.com/)
- [Git Cheat Sheet by GitHub](https://education.github.com/git-cheat-sheet-education.pdf)
- [Git Cheat Sheet by Tower](https://www.git-tower.com/blog/git-cheat-sheet/)


