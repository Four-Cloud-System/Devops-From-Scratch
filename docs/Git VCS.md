#Version Controlling System (VCS) using Git

#We can create branch using GUI or cmd...
After creating a branch in Gitlab we try to see all branches from terminal
	
	
	git branch		---it shows all branches if it shows only master branch that means local repository don't know that we have a new branch, so we need to pull it on our machine....
	
	git pull	
	
	and it will reply 
	
	 * [new branch]      test-branch -> origin/test-branch
Already up to date.	
	
	to switch in new branch-
	
	git checkout 'branch name'
	
	git checkout test-branch	---it will change the current branch to new branch
	
	to change the branch again to master
	
	git checkout master	
	
	to create new branch from terminal
	
	git checkout -b 'branch name'
	
	too see all branches
	
	git branch
	
	new branch created on our local machine so we need to push it from our local machine to remote to push it..
	
	git push --set-upstream origin feature/db 			#its important to set the upstream 