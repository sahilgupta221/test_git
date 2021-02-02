# test_git
Testing branching and merge

Test changes

Important GIT tutorials:
1. https://www.youtube.com/watch?v=uR6G2v_WsRA
2. https://www.youtube.com/watch?v=FyAAIHHClqI
3. https://www.youtube.com/watch?v=Gg4bLk8cGNo

Common commands:
A. branching, pushing it to Github, and  merging with master.
0. alias graph="git log --all --decorate --oneline --graph"
1. git branch b1
2. git commit -a -m "some changes in b1"
3. git push origin b1
4. git checkout master
5. git merge b1
6. remove HEAD marks from conflicted files and keep the merged code.
7. git commit -a -m "final merge of branch b1 with masters" 
8. git push origin
9. git diff master..b1

Unstaging from commit history
git reset HEAD <filename>

changes back to working dir from staging area
git checkout -- s1

Putting head to some commit point in history
git checkout <commit hash value 5 digits>
Pushing local git repository to github:
https://www.softwarelab.it/2018/10/12/adding-an-existing-project-to-github-using-the-command-line/

You can create a local repository and work in it. (branching etc.)
But to provide git repo to other you need to push it to Github.
CMD for pushing changes of a branch:
git push origin b1

Checking out specific branch (git clone -b <branchname> URL)
https://www.freecodecamp.org/news/git-clone-branch-how-to-clone-a-specific-branch/

Keeping branches upto date:
https://stackoverflow.com/questions/20101994/git-pull-from-master-into-the-development-branch

git checkout b1
git fetch origin
git merge origin/master

