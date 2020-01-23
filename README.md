# Tutorial on Git commands and Github
This tutorial will walk us through the workflow of making a commit

## Step 1
Initialize the repository by running the command below
```git
git init
```

## Step 2
Configure your username and email using the commands below
```git
git config --global user.name "[your username]"
```

## Step 3
Add files or alter current project with code below
```git
git add .
```
( . means all, it can be replaced with a file name)

## Step 4
Commit files to branch with code below
```git
git commit -m "[insert message here]"
```

## Step 5
Check branch status with the code below
```git 
git status
```

## Step 6
Check branches by using the code below
```git
git branch
```

## Step 7
Delete branches with the code below
```git
git branch -d [name of branch]
```

## Step 8
Adding branches with the code below
```git
git branch [new branch name]
```

## Step 9 
Move to a different branch using the code below
```git
git checkout [branch name]
```

## Step 10
merge branches using the code below 
```git
git merge [branch to merge with current names]
```

## Step 11
Initialize cloud repository using the git remote add origin "URL" command from github

## Step 12
Commit to cloud repository using the command below
```git 
git push -u origin master
```
Files must be commiting locally first to commit over the cloud

## Step 13 
Check github to confirm push
