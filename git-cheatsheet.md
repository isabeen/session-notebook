# Git Basic Commands

```JavaScript
// change directory
cd

//l ist directory
ls

// print working directory
pwd

// go to previous directory
cd --

// go to previous directory
cd ..

// goes two directories backwards
cd../..

// go to home directory
cd ~

// make directory
mkdir

// add file e.g. touch description.txt
touch

// shows content of the file e.g. cat description.txt
cat

// delete a file
rm

// list hidden directory
ls -la

// rename or move folder or  file
mv <folder to move> <destination>

// e.g mv private notes (This makes a new folder named notes and moves private folder in current directory to the new folder)

// For example, to move a file from your Downloads folder to a Work folder in your Documents folder:
mv ~/Downloads/MyFile.txt ~/Documents/Work/MyFile.txt

// This command helps to see the tree structure of folders
cmd //c tree


// opens folder in vs code
code .

// opens index.html in vs code
code index.html
```

# Git Repository Commands

```JavaScript

// turns folder into a local repository
git init

// If you don’t want a folder to be a repository anymore, just delete the .git (hidden) folder

// checks the status of the repository
git status

// We must have a .gitignore file in the Git repository. In that file, we can add filenames starting with a dot and git will ignore that those files even exist.

// We must also have a README.md file in the Git repository. It has all the information about the project.

// added as changes to be committed, committed to staged
git add README.md


// adds all files to be committed
git add .


// good practice to use lowercase for commit message and message in present tense i.e. Add files instead of added files
git commit -m  “commit message”

// gives us add the previous commit details
git log

// gives just one last previous commit
git log --oneline

// goes backs to the last committed version of your file
git restore  README.md

// restores previous version of all files
git restore .

// gives connection to GitHub
git remote add origin git@github.com…………………


git remote -v

// allows developers to publish their local code changes to a remote repository, specifically the main branch, often referred to as master  (Executed only once at the beginning)
git push -u origin main

//publishes code to the main branch
git push

//downloads latest code
git pull


// cloning repository:
git clone git@github.com:neuefische/tellicherry-ber-web-24-1.git

```

# Git Branch Commands

```JavaScript

// createa a new branch and switch to it
git switch -c <branchname>

// switch branches
git switch <branchname>

// list your branches
git branch

// list your branches (local and remote)
git branch -a

// delete a branch
git branch -d <branchname>

```
