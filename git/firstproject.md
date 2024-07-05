# GIT First Project
- Open GIT Bash

```
mkdir firstproject
cd firstproject
git init
touch sampletextfile.txt
git status
git add .
git commit -m "firstproject's 1st comment"
git config user.name <githubusername>
For ex: git config user.name "pvishnutech"
git config user.email <githubemailid>
For ex: git config user.email "pvishnutech@gmail.com"
```

# Git 2nd Project
```
pwd
cd ..
pwd
mkdir secondproject
cd secondproject 
git clone https://github.com/pvishnutech/testrepo/
cd testrepo
touch 2.txt
touch 3.txt
git add .
git commit -m "2nd project samples files check-in"
# create github repo

```

# Git 3rd Project
```
echo "# 2.2project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/pvishnutech/2.2project.git
git push -u origin main

## added some changes

git push

### we will get an error

git pull
git push
```
