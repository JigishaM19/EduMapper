# EduMapper
----------------------------------
git clone <repo-url> eg. https://github.com/JigishaM19/EduMapper.git
cd <repo-folder> eg.EduMapper 
-------------------------------------------------------------------
git status

---------------------------------------------------------
# make changes
git add .
git commit -m "your commit message"
git push origin <branch-name>
-----------------------------------------------------
#Undo / Reset
git restore <filename>     # undo changes in file

-----------------------------------------------------------
#Merge all branch
git branch -a     #Check Available Branches
git checkout main   #Switch to main Branch
git pull origin main    
git merge <branch-name>  #Replace <branch-name> with the branch you want to merge (e.g., feature1, feature2, etc.).
git add .
git commit -m "Resolved conflicts and merged <branch-name> into main"
git push origin main

----------------------------------------------------------------

#After Mearge 
git checkout main
git pull origin main

------------------------------



