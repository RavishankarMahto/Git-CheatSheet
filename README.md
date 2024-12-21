# Git-CheatSheet
This is the A to Z git command cheat sheet.


Git-CheatSheet/
├── README.md
├── Configuration.md
├── Workflow.md
├── Branching.md
├── Stashing.md
├── Tagging.md
├── UndoingChanges.md
├── AdvancedWorkflow.md
├── TipsAndTricks.md
└── Resources.md

# Git Cheat Sheet

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


# Resources

- [Official Git Website](https://git-scm.com/)
- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Learning Lab](https://lab.github.com/)
- [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials)
- [Git Immersion](https://gitimmersion.com/)
- [Git Cheat Sheet by GitHub](https://education.github.com/git-cheat-sheet-education.pdf)
- [Git Cheat Sheet by Tower](https://www.git-tower.com/blog/git-cheat-sheet/)
