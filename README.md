# About
Personal guide on how to use git

  
# Definitions
## Parts of Git
  
1. Working Directory
2. Staging Area
3. Local Repository
4. Remote Repository
  
## More on Parts of Git
  
- Untracked file
- In working directory; NOT in staging area
- To add it to staging area: git add [file]
- Changes to be committed
- In staging area; NOT in local repository
- To add it to local repository: git commit -m 'comment'
- Your branch is ahead of 'origin/main' by 1 commit
- In local repository; NOT in remote repository
- To add it to remote repository: git push origin main
- origin - remote name
- main - branch name to push in

# Creating a New Project Starting Remotely

1. Create the repo on GitHub with a README.md file
2. Clone it locally
- git clone [link to repo]
3. Add new files
4. git add
5. git commit -m 'commit message'
6. git push origin main

# Creating a New Project Starting Locally

1. git init [project-name]
2. cd [project-name]
3. create new files in [project-name]
4. git add
5. git commit

# Adding Git to an Old Project Locally

1. cd [path-to-old-project]
2. git init
3. git add .
4. git commit

# Joining an Existing and Remote GitHub Project
1. Go to the repo on GitHub
2. Click the fork button
3. Go to the newly forked repo
4. git clone [link to newly forked repo] 
