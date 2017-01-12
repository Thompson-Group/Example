Example
This is an example repository

Step by Step instructions.

1.) Clone the Repository
git clone https://github.com/Thompson-Group/Example.git

2.) Create a new Branch.
git checkout -b newbranch

3.) Push Branch to github
git push origin newbranch

4.) Make a change to whatever file you want.

5.) Add the file to commit to the branch.
git add test.dat

6.) Commit the change
git commit -m "Commit Message"

7.) Update your branch to most recent version
git checkout newbranch
git pull origin newbranch

8.) Update master to most recent version
git checkout master
git pull origin master

9.) Begin the merge
git merge --no-ff --no-commit newbranch

10.) Check the merge for changes 
git status

11.) Actually commit the branch.
git commit -m 'merge test branch'
git push
