# Git Tutorual
This is Git tutorial
<!-- # will work for heading & ## work for subHeading -->
# Git Commands

## git init
    This will initialize the git in working directory.

## git status
    This will show all files which are not tracked & and modified but not added or commit

## rm -rf .git
    This will delete .git folder.
    When .git folder is delete there is no git log or other things

## git add <filename>
    This will add file to the stage for commit.
    If you write <code>git add .</code>. then this will add all modified files and untracked files to staged file.

## git commit
    this will make all staged file as commit.
    <code>-m <Titla of commit> -m <Description of Comit></code>
## git log
    this will list all previous history of the project of commits
    press 'q' for quit from this mode
        
## git ignore (this is not command)
    make a file .gitignore
        All files that you want to ignore from tracking can listed here in .gitignore file
    ### add file for ignore
        text.log --> It will ignore a file name as text.log
        *.exe --> It will ignore all files which have .exe extensino
