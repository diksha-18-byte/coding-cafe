1   --global applies my name and email across my entire system saving it in global config file but if i left it out, git would only set those details for the current repository I'm standing in,
    and i'd have to configure them again for every new project.
2.  ls -a revealed the hidden .git folder which doesn't show up in ls command. inside it lives  git's internal data base, including commit history, branch refrences, configuration settings and
    staging data that power version control.
3.  Git offered to track a dozens of files across my directory, including existing lab scripts and config files. The .venv/ folder definitely isn't code I wrote—it contains thousands of auto-generated 
    virtual environment files installed by Python packages.
4.  After adding .gitignore, all the junk files and folders listed inside it (like.venv/etc) completely dissappeared from the untracked list in git status. Now git only displays the actual project files I 
    care about tracking.
5.  Yes,.gitignore absolutely needs to be committed rather than ignored. It’s a project configuration file, and committing it ensures everyone collaborating on the repository automatically ignores the same 
    temporary or sensitive files.
6.  It moves from 'untracked files' to 'changes to be commited'. In three places model it moves from the working directory to the staging area.
7.  It prints branch name,commit hash snippet, commit message, number of files changed and insertion counts.
8.  It is a short SHA-1 hash.it serves as a unique identifire for that specific commit in git history. 
9.  Make changes, check current git status, stage the updates with git add, record the snapshot or save with git commit.
10. Github automatically detects and render README.md on the root repository page to introduce the project.
11. It creates and stores an authenticated credential token locally so git doesn't ask for a password on future pushes.
12. README.md is rendered automatically because github uses it as the default display overview.
13. No, git push uplods local commits to the remote server and it doesn't modify local history.
14. A private repository exists on github's servers and is accessible only to invited collabrators.A non-existent repository does not exist anywhere on github.


