# EduMapper

## 🚀 Git Workflow

```bash
# Clone Repository
git clone <repo-url>    # e.g. https://github.com/JigishaM19/EduMapper.git
cd <repo-folder>        # e.g. EduMapper

# Check Status
git status

# Make Changes & Push
git add .
git commit -m "your commit message"
git push origin <branch-name>

# Undo / Reset
git restore <filename>     # undo changes in file

# Merge All Branches into main
git branch -a              # check available branches
git checkout main          # switch to main branch
git pull origin main       # update main
git merge <branch-name>    # merge branch (e.g., feature1, feature2, etc.)
git add .
git commit -m "Resolved conflicts and merged <branch-name> into main"
git push origin main

# After Merge (for all users)
git checkout main
git pull origin main
