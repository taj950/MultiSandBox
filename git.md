# Git commands #
## How to use git clone command 
* 1 Obtain the Repository URL

    Navigate to the repository’s main page on GitHub (or your preferred Git hosting service).

    Click the Code button (usually green) above the list of files.

    Copy the URL provided (choose HTTPS or SSH, depending on your setup)
* 2 Run the git clone Command

    Type the following, replacing <repository-url> with the URL you copied:
    git clone <repository-url> 
    done.
## How to git config 
* 1 Set your username and email (required for commits):

  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"

    --global applies these settings to all repositories for your project--
## How to use git add ##
* 1 To use git add, follow these steps:

    Check Your Changes
    Run git status to see which files are new, modified, or deleted in your working directory

.

* 2 Add Files to the Staging Area

    Add a specific file:
   git add filename

* 3 Add all files in the current directory
  git add 
## How to use git commit ##Push Your Commits

    To push your current branch to the remote repository:

bash
git push origin main

(Replace main with your branch name if different.)
 * 1 To use git commit, follow these steps:

    Stage Your Changes

        Before committing, add your changes to the staging area using:

bash
git add <file>

Or add all changes:

    bash
    git add .
* 2 Commit Your Changes

    To commit the staged changes with a message, use:

 git commit -m "Your commit message"

  This creates a snapshot of your current files and saves it to your repository with a descriptive message

  Note: If you omit -m, Git will open your default text editor for you to write a longer commit message
## how to use git status ##
 Run the command:
  git status
 ## how to use git 




  




### 
