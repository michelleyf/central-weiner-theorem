# central-weiner-theorem

## Git Level 0
These commands are meant to be run from terminal.

1. ```git <command> --help``` opens the relevant documentation page
2. ```git clone <link>``` creates a subfolder with "repo-name" then clones the entire project in it.
   1. This happens in your current directory on terminal, so navigate there first.
3. ```git status``` tells you which branch you are on (don't work on master please)
4. ```git switch <branch-name>``` switches to branch "branch-name"
5. ```git commit -a -m "Message"``` Adds ('-a') modified files and commits them, with an accompanying explanatory message ('-m "Message"')
6. ```git pull``` Pull changes that others have pushed
7. ```git push``` Push your code changes for others to pull

### Simplified example workflow
1. ```git status``` and ```switch``` away from master if necessary
2. ```git pull``` to be updated.
3. Modify file (We only have one)
4. ```git commit -a -m "I did stuff"``` to lock in your code changes.
   1. Don't bother reverting commits, just edit and commit again over them.
5. ```git push``` to push your updates out to Github

### FAQ/Weird Stuff
* Pulling regularly minimizes conflicts. We'll deal with merge conflicts only if they happen.
* ```git add .``` stages all changes (but allows you to undo using ```git add .``` again since no commit is made). It is implicit as the -a flag in the comment line.
* ```commit``` commits changes locally, while ```push``` sends these out to the Github's branches and ```pull``` retrieves others' changes from Github's branches.