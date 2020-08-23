# dan_chen_course_collaboration_kai
git collaboration part 2 course

 - git vlone '<URL>': downloads the repository from the web to the local computer
 	- make sure you DONT nest repository into another repository
	= only do this once per repo >> .git into .git (this is GIT submodules

## Branches
 - 'git branch <branch name>: create a new branch where HEAD is
 	-'git branch -a': list all branch on your local machine
 - 'git switch <branch name>:move to branch
 	- 'git checkout <branch_name>': the pre-agust 2019 way

 - git switch -c <branch>: create and move to branch in 1 step
    - git checkout -b <branch>

 - git log --oneline --graph --decorate --all : shows git history tree
      - you can look up how to set this as an igt alias

  - git fetch --prune: clean your git history and remove references from remote that  no longer exist

  -git branch -d :moves brance from your local computer 

  -Pull request: when you push a branch to a remote and merge the branch and the online interface


