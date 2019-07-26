# working directory
areas where all our files and changes are living all the time.

# staging area
where files are kept temporaly (git add)

# git repository
where ll our snap shots are stored (git commit)

# common command

git init
git add <file>
git commit -m " "
git log
git status

# to add  files
git add*.html --add a particular type of files.
git add -A -- add all files and folders in the directory.

# to remove files
git rm --cached <file>.
git reset HEAD <file> to unstage.

# to ignore  files 
create a file named .gitignore and add the names of all the files you want to ignore inside the .gitignore file.

# branch
to create new branch -- git checkout -b <branch_name>
branch list --git branch.
to move from one branch to another -- git checkout <branch_name>.
to merge branch -- git merge <branch_name>.
to remove a branch -- git branch -d <branch_name>.
# github

setup --git remote add origin url
push --git push -u origin master.
