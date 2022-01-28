# Git CLI Quiz

Remember, you must submit this quiz using __ONLY__ Git on the Command Line.

You __CANNOT__ open Github Desktop.

---

1. What is a benefit of using the Git CLI rather than a GUI?

my answer is:

That a GUI does not have the same level of flexibility as a command line interface. In general, it is easier to do things using the command line interface that are difficult (or even impossible) to do with a GUI.

2. What is the Git command to send your code to Github?

git push <name of remote> <name of master branch> 
e.g.
git push origin master

3. What does the -m in a Git commit command mean or do?

This adds a user comment to the changes made. 'm' basically stands for 'message' 
The purpose of this message/comment is to inform/remind the user the reasons behind the commit.

4. What is the Git command for making a commit?

git commit
EG
git commit -m "commit message"

5. What is the Git command to select the files you want to add to a commit?

git add <filename>
This adds the file to the 'staging area'

git add .
This command will add every file you have changed to be ready to commit


6. What is the Git command to see changes you have waiting to be committed?
git status

7. What is the Git command to get changes from Github onto your computer?

git pull <name of remote> <name of master branch> 
e.g.
git push origin master
