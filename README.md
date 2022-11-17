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

## git add `filename`
    This will add file to the stage for commit.
    If you write 'git add .' then this will add all modified files and untracked files to staged file.
## git commit
    this will make all staged file as commit.
    git commit -m "Title of commit" -m "Description of Commit"
    git commit -a -m "Title of commit" -m "Description of commit" --> This will commit all modified files direct without go to staged.
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
## git rm `fileName`
    It will remove file and automatically staged it.
## git mv `currentFileName` `newFileName`
    It will rename the file and automatically staged it.

## git rm --cached `fileName`
    It will remove file from tracking any more.
## git log -p
    It will give detailed log of old commits.
    `git log -p -n` n = number of recents commits you want to see.
## git log --stat
    It will give brief details of old commits.
## git log --pretty=oneline
    It will give one line details of old commits.
    `git log --pretty=short` will give short details of old commits
## git log --since=2.days
    It will give all last 2 days commits.
    `2.days,2.weeks,2.months,2.years` You can get all these type of details
## git log --pretty=format:"here you can add any type of format"
----- [Git pretty Log formats](https://git-scm.com/docs/pretty-formats "https://git-scm.com/docs/pretty-formats") --> you can go this website and check types of formats.

## git commit --amend
    This will ammend your new staged changed to last commit & edit last commit
