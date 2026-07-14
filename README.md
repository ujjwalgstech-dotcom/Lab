Exp 1

git --version

git config --global user.name "Name"

git config --global user.email "Email"

mkdir GitLab

cd GitLab

git init

echo "Hello Git" > file.txt

git status

git add file.txt

git commit -m "First commit"

git log

Exp2
git config --global user.name "Name"

git config --global user.email "Email"

mkdir git23

cd git23

git clone <repository-url>

cd <repository-folder>

echo "Hello Git" > file.txt

git status

git add .

git add file.txt

git status

git commit -m "First commit"

git push -u origin main

git status

Exp3

mkdir git23

cd git23

git fetch origin

git merge origin/main

git pull origin main

git log

Exp 4
mkdir git23

cd git23

git branch

git branch feature

echo "Feature Branch" >> file.txt

git status

git add .

git commit -m "Added feature"

git checkout main

git merge feature

git log --oneline

git branch -d feature

git branch test

git checkout test

echo "Testing Rebase" >> file.txt

git add .

git commit -m "Test commit"

git checkout main

git rebase test

git log

Exp 5
mkdir git23

cd git23

git status

echo "New changes" >> file.txt

git status

git stash

git stash list

git branch feature

git checkout feature

git stash apply

git status

git add .

git commit -m "Applied stash changes"

git stash drop

git stash list

Exp 6

cd git23

ls

git branch

git checkout -b feature-login

git branch

echo "Login Feature Added" >> file.txt

git status

git add .

git commit -m "Added Login Feature"

git push -u origin feature-login

git checkout main

git pull origin main

git log --oneline

git status

Exp7


cd git23

ls

cd git23

git status

echo "Modify" >> file.txt

git status

git add .

git commit -m "Save changes"

git rebase -i HEAD~2

# Press Esc
# Type :wq
# Press Enter

git tag v1.0

git tag

git push origin v1.0

Exp 8

# Create any 5 commits by creating directories/files

cd git23

ls

cd git23

git status

git log -5

Exp 9
cd git23

ls

cd git23

git branch

git checkout main

git log --oneline

git status

git cherry-pick <commit-id>

git cherry-pick --skip

git status

git log --oneline

git status

git log -5

git log --author="JohnDoe"

git reset --soft HEAD~1

git status

git add .

git commit -m "Test commit"

git log --oneline

git revert <commit-id>

# Press Esc
# Type :wq
# Press Enter

git revert -m 1 HEAD

git log --oneline

git status

Exp 10

cd git23

ls

cd git23

git status

git log -5

git log --oneline -5

git log --author="name"

git status
