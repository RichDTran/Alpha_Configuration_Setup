# Useful Git Commands

## Learning git and Github with Alpha

### Useful Commands
- git clone file-name
- git status
- git add file-name
- git commit -m "meaningful message here"
- git push origin main

### Vocabulary

- repository (repo) - a named folder on GitHub
- git - version control software
- GitHub - online platform for git, GUI for sharing code and collaboration
- local - your personal computer
- commit - adding a tracker number and message to your version
- diff - the difference between states of your local and Github repository
- markdown (.md) - a text-based language used on GitHub for code documentation

### Reasons!

- Github is a website online to store and create code connecting from your local computer
to the internet.
- This is a great tool that is used to see your work and so employers and others can also see
what you have done.

### Git process Notes
- create a new repo on Github
- clone the repo to your local
- add a new file
- add code to the file
- use git status to see where you are in at the process
- add,commit, push code to GitHub.

### Branching Vocab
branching-commands

- branch - an alternative timeline where a developer can code safely
- main - the branch that is the source of truth, only working code allowed
- checkout - command to navigate between branches
- checkout -b - creates a new branch that doesnt currently exist
- deleteing a branch - has to be deleted on local and on Github

### Notes About Branching
branching-commands

- Branching protects your code from errors that can cause your app to be down in production
- Branching allows multiple people to work on code at the same time
- Branching is a best practice for all developers on all porjects
- The main branch is the source of truth and should only ever have working code
 branching-commands

 Branching Commands

- $ `git checkout -b branch-name` - creates a new branch that doesnt exist
- $ `git branch` - lists all the current branches on your local
- $ `git branch` -d branch-name` - deletes a branch when you are done
- $ `git checkout main` - navigates back to the main branch