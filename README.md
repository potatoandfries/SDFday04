# SDFday04

first step:

git init >> makes a repo in GH (local side)
go github make one repo(online) 

e.g:
echo "# SDFday04" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:potatoandfries/SDFday04.git
git push -u origin main

how to check? 
git remote -v

then we make  two directories:
mkdir classes
mkdir src
>> creates two directories

make .gitignore by :
code -r .gitignore
(since we are windows )

git status
git add (file name)
git commit -m "blah"
 git push --set-upstream origin main


// Git will ignore the specified patterns and files. Here's what each of these lines means:

classes: This line will ignore the classes directory in your Git repository. If you have a directory named classes, it won't be tracked by Git.

*.log: This line will ignore all files with the .log extension. Any file with a .log extension will not be tracked by Git.

*.tmp: This line will ignore all files with the .tmp extension. Files with a .tmp extension will not be tracked by Git.

Make sure that your .gitignore file is placed in the root of your Git repository, and Git should start ignoring the specified files and directories that match these patterns. This is useful for excluding build artifacts, log files, temporary files, or any other files or directories you don't want to include in your version control.
//



