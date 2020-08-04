# HackOurCampus Git Workshop
In this repo we will practice using branches, committing code, and opening pull requests (PRs) by checking in your information! 🚀🚢

## Prereqs:
- make sure you have [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed and are logged in to your GitHub account on Git
- you can either use the Git command line or the GitHub Desktop app. If you're using GitHub Desktop make sure you have it installed from [here](https://desktop.github.com/).
- you have some kind of text editor. We recommend VSCode, install it [here](https://code.visualstudio.com/download)

## Steps
1. Clone this repository. Click the green `Code` button. 
    - GitHub desktop: click `Open with GitHub Desktop` and that should take you to the desktop application and ask where to save things. Once you're done hit `Clone`. 
    - Git command line: run `git clone <url>` where `<url>` is the HTTPS url of the repo in the input box.
2. Create a branch named `<netid>` with your NetID.
    - GitHub desktop: Do CMD+N or click the `Current Branch` tab on top and then `New Branch`.
    - Git command line: `git checkout -b <netid>`
3. Open the repository in your text editor.
    - GitHub Desktop: click `Open with VSCode`
    - Git command line, navigate to the folder you cloned the repo in and open it in VSCode or your favorite text editor
4. Create a file named `<netid>.md` where `<netid>` is your Cornell NetID.
5. Copy the contents of `my474.md` into your new file. This is Megan's profile information but you'll populate it with your information :)
6. Remove all of Megan's information (but keep the labels!) and enter your information instead. Don't forget to save!
7. Add and commit your changes.
    - GitHub Desktop: fill in the commit message (input box with default text `Update README`) and click the blue `Commit to <netid>`. The `Description` input is optional.
    - Git command line: run `git add <netid>.md` and then `git commit -m "<msg>"` where `<msg>` is your commit message
8. Push your changes.
    - GitHub Desktop: Click `Publish branch` button on the top tabs.
    - Git command line: `git push -u origin <netid>`
9. Create a pull request
    - GitHub Desktop: Click the `Create pull request button`.
    - Go to [https://github.com/HackOurCampus/git-workshop](https://github.com/HackOurCampus/git-workshop) and (if you are logged in) you should see a prompt in yellow with your branch name and a green button `compare and pull request`. Click that.
10. Fill out pull request
    - Add a title and description on the web interface! Be sure the title has your name and netid :)
11. Wait for @meganyin13 approval review! 👩🏻‍💻
12. Once you've received approval, click `squash and merge`.

## Congrats!! 🚀

You have now learned the Git workflow and created a pull request (PR)! See you at the hackathon!
