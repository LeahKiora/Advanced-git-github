# Advanced-git-github
 git clone https://github.com/LeahKiora/Guess-the-Number_Coding-with-Python.git
 3. Creating and Switching Branches
 Create a new branch:
 git branch feature-update
Switch to the new branch:
git checkout feature-update
4. Making Changes and Committing:
git add .
git commit -m "Add new feature or update file"
5. Merging Changes:
Switch back to the main branch:
git checkout main
Merge changes from the feature branch:
git merge feature-update
6. Creating Conflicts:
7. Resolving Conflicts:
Create a new branch for conflict resolution:
git checkout -b resolve-conflict
Pull the latest changes to ensure the conflict is present:
git pull origin main
Commit and merge:
git add .
git commit -m "Resolve conflict"
git checkout main
git merge resolve-conflict
Push all changes to your forked repository:
git push origin main


