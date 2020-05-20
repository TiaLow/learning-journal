# Revisions and the Cloud - 03 reading notes

## Lab 03 Takeaways
- make sure to always ACP!
- during C, if you forget -m "message" after git commit, a new page will pop open in VS Code and you'll have an opportunity to write a commit message there 
    - if that happens, you can right click and delete that pop up, git status back in Terminal and then git commit -m "  " from there 
- use git status liberally, helps to get used to the commands and remembering where you are
- just keep doing this! practice is what makes you better 
- 'doh' moments are unavoidable 

### **Make sure you're working w head locally**
*get to the folder you'd like the repo to live in and type **git clone link** (copied from github) to put it there locally*
*git pull origin master*

## GIT WORKFLOW

git status

git add filename or .

git status

git commit -m "   "

git status

git push origin master

## 03 Reading Notes

**GIT IS A VERSION CONTROL SYSTEM**

- CVCS (Centralized Version Control System) was developed because of the need for collab within a team on a single file or set of files
    - *vulnerability was server as single point of failure*
- DVCS (Distributed Version Control System) allows clients to create mirrored repositories, data backups on a server

**commits** are the Git equivalent of **Save As**

- Files in git reside in 3 main states
    1. **Committed**- data is securely stored in a local database
    2. **Modified**- file has been changed but not committed to database
    3. **Staged**- flagged a file's changed version to be committed in next snapshot

- All files in a working copy of project file are either in tracked or untracked state
    1. **Tracked**- can be modified or staged, were part of most recent file snapshot
    2. **Untracked**- not in last snapshot and are not currently in staging area

- Stashing changes
    - git stash : not ready to commit changes but don't want to lose them
        - temporarily removes changes and hides them
    - git stash apply : command to retrieve hidden changes


[Back to home](README.md)
