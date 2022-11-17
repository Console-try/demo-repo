# Git Tutorual
This is Git tutorial
<!-- # will work for heading & ## work for subHeading -->
# Git Commands

## git init
    This will initialize the git in working directory.

## git status
    This will show all files which are modified & not tracked.

## rm -rf .git
    This will delete .git folder.
    When .git folder is delete there is no git log or other things.

## git add <filename>
    This will add file to the stage for commit.
    If you write 'git add .' then this will add all modified files and untracked files to staged file.
## git commit
    this will make all staged file as commit.
    git commit -m "Title of commit" -m "Description of Commit"
## git log
    this will list all previous history of the project of commits
    press 'q' for quit from this mode
        
## git ignore (this is not command)
### -----make a file .gitignore
        All files that you want to ignore from tracking can listed here in .gitignore file
### -----add file for ignore
        text.log --> It will ignore a file name as text.log
        *.exe --> It will ignore all files which have .exe extensino
### -----ignore folders or Directory
        dir/ --> It will ignore all folders or subfolder name like 'dir'.(only ignore these directory and files that are present in this directory not folders/directory.)
        /dir/ --> It will ignore dir folder only present in current directory.
## git diff
    It will show files difference or changes in file in between modified and staged files.
    git diff --staged --> It will compare staged files with last commited files
