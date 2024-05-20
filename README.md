# This is a Test GitHub Repo

## Learning goals:

1. Clone repo
2. Branch off Dev branch to create a feature
3. Commit changes locally
4. Push changes to remote branch
5. Create a Pull Request when done with feature
6. Merge into main



## Steps:

1. Clone Repository
	Open a terminal in a folder where you want this repo to live.
	Use the following command to clone the repo:
		git clone https://github.com/Endermandels/GitHubPractice.git
	You should now see a folder named GitHubPractice.
	Make sure you have a terminal open in the GitHubPractice folder for the following steps.
2. Pull Changes from Remote
	Always pull before starting new changes.
	Use the following command to pull changes from the remote branch of main:
		git pull
3. Create Dev Branch
	Use the following command to create a local version of the dev branch:
		git checkout -b dev
	You should now be on the dev branch.
4. Pull from Dev Branch
	Always pull before starting new changes.
	Use the following command to pull changes from the remote branch of dev:
		git pull
5. Create Feature Branch
	Use the following command to create a local version of your feature branch:
		git checkout -b elijah/feature
	You should now be on the elijah/feature branch.
	Use your name instead of elijah.
6. Ignored Folder/Files
	Add a folder named "ignored_folder" to your local repo folder.
	Notice that in the .gitignore file, ignored_folder is listed.
	This means that when you go to commit changes,
	all contents in that folder will be ignored.
