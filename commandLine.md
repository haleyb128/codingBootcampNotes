# Commands:

## pwd
Lists the present working directory
## cd < directoryName >
changes present working directory (accompanied by name of desired directory- if not, goes to home)
## mkdir < directoryName >
makes a new directory inside PWD called directoryName
## rmdir < directoryName >
removes a directory called directoryName
## touch < fileName >
makes a new file called fileName in PWD
## rm < fileName >
removes a file called fileName
## ls < directoryName? >
lists all files in PWD or in directoryName
## clear
clears text off terminal (scrolls down)


### Special Directories
~ - Home
<br>
.. - Up a level
<br>
. - Same level
<br>
/ - The root directory (could be c:/ in windows)

# GIT commands

When pushing to github, follow these steps:
    1. `git add <fileName>`
        -This adds fileName to changelist.
        -Use `git add .` OR `git add -A` to add everything to the change list.
    2. `git commit -m "<message>"`
        -If you forget `-m` you will be in VI (a command line test editor). Type `i` then type your message, then press `esc`, then `:wq` and finally enter.
    3. [Optional] `git pull`
        -Use this only if there are other changes not already in your local copy.
    4. `git push <server?><branch?>`
        -Sends your commits to the server.
        -You can usually just do `git push`
        -Otherwise use `git push origin master`

## clone < repoURL >
Downloads from repository to your local PWD
## init
Starts a local git repository
## add < files >
Tracks file or folder (you can use "git add ." to track everything)
## commit < -m > < message >
Takes a snapshot of the directory
## push <server?> <branch?>
Sends your commits to the server
## pull <server?> <branch?>
Receives commits from the server
