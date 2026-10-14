1. WHAT IS GIT?
--> Git is a free, open-source version control system. It helps developers track changes in their code, save different versions of a project, and work on different features without losing previous work.
--> Example: If I accidentally change my code and want to check an earlier version, Git hlps me view the changes and recover previous versions.

2. WHAT IS GITHUB?
--> GitHub is an online platform for hosting Git repositories.It allows developers to store their projects online, share code, collaborate with others, and manage projects together.
--> Example: I can upload my project from my computer to GitHub so that my teammates can view and contribute to it.

3. IMPORTANT GIT COMMANDS:
> git init 
Meaning: Initializes a new Git repository in the current folder.
Example: git init
Use: To start tracking a project with Git.

> git clone
Meaning: Copies an existing remote repository to my computer.
Example: git clone https://github.com/username/project.git
Use: To download a project from GitHub.

> git status
Meaning: Shows the current state of the repository, including changed, staged, and untracked files.
Example: git status
Use: To check which files have changed.

> git add
Meaning: Addsw file changes to the staging area before committing them.
Example: git add README.md
To stage all changes:- git add .
Use: To select which changes I want to include in the next commit.

> git commit
Meaning: Saves the staged changes as a commit in the repository's history.
Example: git commit -m "Add README File"
Use: To record a meaningful checkpoint in my project.

> git log
Meaning: Displays the commit history.
Example: git log
For a shorter history:- git log --oneline
Use: To see previous commits and their messages.

> git diff
Meaning: Shows differences between file versions or changes that have not been staged.
Example: git diff
To view staged changes:- git diff --staged
Use: To review changes before committing.

> git branch
Meaning: Lists branches in the repository.
Example: git branch
To create a new branch:- git branch feature-notes
Use: To organize work into separate development branches.

> git switch
Meaning: Switched to another existing branch.
Example: git switch feature-notes
To create and switch to a new branch:- git switch -c feature-readme
Use: To work on a feature separately from the main branch.

> git merge
Meaning: Combines changes from one branch into the branch I am currently on.
Example: git switch main
         git merge feature-notes
Use: To combine completed feature work into another branch, I should merge only when permitted by the project's workflow.