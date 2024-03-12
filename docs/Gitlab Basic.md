
# Basic Gitlab Commands

step 1 	create a repo in gitlab
step 2		open a project from localmachine.
step 3		u can use direct terminal or text editor to connect with repo in my case I use VSCode with my project.
step 4		after opening project in vscode open terminal and follow commands:
		
		git status		-----to see the branch of files, all file names will shown in red colors cause files are not initialized 
		
		git init	----it initialize the project
		
		git add .  -(If want to upload specific file then write command 'git add <filename>')
		
		git status	it will show all file names are in green color
		
		git commit	---it will ask for comments for new commit, it will help to recognize the changes.
		
		previous 5 steps made a local commit for changes 
		
		git remote add origin git@gitlab.com:rahul1564303/simple-calculator-nodejs-devops-practice.git 		----it will add remote origin where the changes will uploaded.
		
		then we have to push the changes to gitlab using the branch name, in my case I use master-branch
		
		git push --set-upstream origin master
		
		refresh the project url from browser and BOOM you will see the changes...
		
		in your local machine on project folder there is file named ".git" it makes the connection to your pc to remote gitlab repo. If you want to revoke the connection then just delete the ".git" file! You can Also remove this file using command prompt "rm -rf .git"
