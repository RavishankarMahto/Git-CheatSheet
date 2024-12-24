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
