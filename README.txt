Hello Git and GitHub


mkdir git_practice to make a new directory to practice.
cd git_practice to make the new directory your working directory.
git init to turn the current, empty directory into a fresh Git repository.
echo "Hello Git and GitHub" >> README.txt to create a new README file (more on this later) with some sample text.
git add README.txt to add the new file to the Git staging area.
git commit -m "First commit" to make your first commit with the new README file.

git remote add origin https://github.com/kentum2/git_practice.git
git push -u origin master
git checkout HEAD filename: Discards changes in the working directory.
git reset HEAD filename: Unstages file changes in the staging area.
git reset commit_SHA: Resets to a previous commit in your commit history.
git branch: Lists all a Git project's branches.
git branch branch_name: Creates a new branch.
git checkout branch_name: Used to switch from one branch to another.
git merge branch_name: Used to join file changes from one branch to another.
git branch -d branch_name: Deletes the branch specified.
