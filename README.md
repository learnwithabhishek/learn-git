# learn-git
Learn git commands
Basic Git commands

•	Set global username and email for Git (Locally)
	git config --global user.name “<your user name>”
	git config --global user.email “<your email>”
	Initialise an empty git repository 
	git init
	Clone an existing Git Repository
	git clone <repository_url>
	Add file/stage to git
              git add <filename>
	Add all the current directory files to git
             git add .
	Commit all the staged files to git
            git commit -m "<your_commit_message>"
	Restore the file from being modified to Tracked
git restore <file name> , git checkout <file name>
	Show the status of your Git repository
— git status
	Show the branches of your git repository
— git branch
	Checkout to a new branch
— git checkout -b <branch_name>
	Checkout to an existing branch
— git checkout <branch_name>
	Remove a branch from Git
— git branch -d <branch_name>
	Show remote origin URL
— git remote -v
	Add remote origin URL
              — git remote add origin <your_remote_git_url>
	Remove remote origin URL
             — git remote remove origin
	Fetch all the remote branches
             — git fetch
	Push your local changes to remote branch
             — git push origin <branch_name>
	Pull your remote changes to the local branch
             — git pull origin <branch_name>

	Check your git commits and logs
              — git log
