
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
- Your branch is ahead of 'origin/master' by 1 commit
	- In local repository; NOT in remote repository
	- To add it to remote repository: git push origin master
		- origin - remote name
		- master - branch name to push in  

# Creating a project

1. Create the repo on GitHub with a README.md file
2. Clone it locally
- git clone [link to repo]
3. Add new files
4. git add
5. git commit -m 'commit message'
6. git push origin main
