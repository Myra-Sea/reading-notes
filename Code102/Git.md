# Git

*Version Control is a system that allows multiple versions of a file to be saved by recording the changes made.  This allows previous versions to be revisited, modifications to be easily seen, and mistakes to be easily rectified.*

*Distributed Version Control System (DVCS) is a system that allows clients to create multiple, mirrored repositories.  This allows for easier backup and for multiple developers to work on the same code, allowing collaboration.*

*Git is a type of DVCS.  It keeps a history of changes by storing snapshots of each file, with a reference to it, every time that file is changed.*

*Cloning is a command that copies all versions of all files for a project.  The copies are automatically placed in a directory called "test" that contains the initialized .git directory inside.  The name of the directory can be changed during the cloning process.*

<br>

<br>

![swirly divider line](divider.gif)

## The Git ACP Commands

**git add** tracks and stages files in preparation for committing.  A space followed by a period can be added to the end of the command in order to track and stage all of the recently changed files in the current directory.  

**git commit** takes a snapshot of changed files.  Add `-m` and a description of changes made inside of quotation marks to the end in order to record what was changed.  For example, ***git commit -m "Fixed typos"***

**git push** is the command that should be used to send changed files to a remote repository.  For sending to GitHub it should be followed by "origin main"  so that the command reads ***git push origin main***

<br>

![swirly divider line](divider.gif)

## Assigned Reading

[Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
