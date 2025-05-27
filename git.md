# Git commands #
##1. How to Use git clone

Step-by-Step:

    Obtain the Repository URL

        Go to the repository’s main page on GitHub (or your preferred Git hosting service).

        Click the Code button (usually green) above the list of files.

        Copy the URL provided (choose HTTPS or SSH as needed)

        .

    Run the git clone Command

        Open your terminal or command prompt.

        Type the following, replacing <repository-url> with the URL you copied:
ex:
```bash
git clone https://github.com/taj950/MultiSandBox.git
```
    This creates a local copy of the repository on your machine

    .

##2. How to Use git config

Set Your Username and Email (Required for Commits):

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
ex:
```bash
git config --global user.name "taj950"
git config --global user.name .email"taj95020@ gmail.com"
```
    --global applies these settings to all repositories on your computer
Tip: You can also set these per repository by omitting --global and running the command inside the repository directory

    .

##3. How to Use git add

Step-by-Step:

    Check Your Changes

        Run git status to see which files are new, modified, or deleted.

    Add Files to the Staging Area

        Add a specific file:

```bash
git add filename
```
Add all files in the current directory:

        bash
        git add .

##4. How to Use git commit

Step-by-Step:

   1) Stage Your Changes

        Use git add <file> or git add . as above.

    2) Commit Your Changes

        To commit the staged changes with a message:
```bash
git commit -m "Your commit message"
```
ex:
```bash
git commit -m "its ok now"
```
This creates a snapshot of your current files and saves it with your message

 Note: If you omit -m, Git will open your default text editor for a longer message.

##5. How to Use git push

Push Your Commits to the Remote Repository:
ex:
```bash
git push origin main
```
    Replace main with your branch name if different.

##6. How to Use git status

Check the Status of Your Repository:
ex:
```bash
git status
```


### 
