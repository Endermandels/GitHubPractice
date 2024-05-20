# This is a Test GitHub Repo

## Learning goals:

1. Clone repo
2. Branch off Dev branch to create a feature
3. Commit changes locally
4. Push changes to remote branch
5. Create a Pull Request when done with feature
6. Merge into dev



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

7. Commit Changes

	Add or change some files in the src folder.
	To add those changes to the commit schedule, use the following command:
		git add .
	Make sure you are in src when using the above command.
	To commit those changes, use the following command:
		git commit -m "commit message"
	Make sure that the commit message is short and dense

8. Pushing to Origin

	To push your committed changes FOR THE FIRST TIME, use the following command:
		git push --set-upstream origin elijah/feature
	For subsequent pushes on this branch, use the following command:
		git push

9. Pull Request

	Once your feature is done, create a Pull Request to merge it into the dev branch.
	At the top of the GitHub repo, you should see an orange notification about recent pushes.
	Click the Compare & pull request button.
	Towards the top, you should see two drop-down boxes showing which branches are being merged.
	Change the left branch from main to dev.
	Write a short description for the changes made on your feature branch.
	Then click on Reviewers to the right and select Endermandels (that's me, Elijah).
	Once you are done, click on Create pull request at the bottom.

10. Finished

	Congratulations!
	You have finished the quick GitHub tutorial I created.
