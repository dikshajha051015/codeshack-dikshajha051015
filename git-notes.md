1. WHAT IS GIT?
<br>
--> Git is a free, open-source version control system. It helps developers track changes in their code, save different versions of a project, and work on different features without losing previous work.
<br>
--> Example: If I accidentally change my code and want to check an earlier version, Git hlps me view the changes and recover previous versions.

2. WHAT IS GITHUB?
<br>
--> GitHub is an online platform for hosting Git repositories.It allows developers to store their projects online, share code, collaborate with others, and manage projects together.
<br>
--> Example: I can upload my project from my computer to GitHub so that my teammates can view and contribute to it.

3. IMPORTANT GIT COMMANDS:
> git init 
<br>
Meaning: Initializes a new Git repository in the current folder.
<br>
Example: git init
<br>
Use: To start tracking a project with Git.

> git clone
<br>
Meaning: Copies an existing remote repository to my computer.
<br>
Example: git clone https://github.com/username/project.git
<br>
Use: To download a project from GitHub.

> git status
<br>
Meaning: Shows the current state of the repository, including changed, staged, and untracked files.
<br>
Example: git status
<br>
Use: To check which files have changed.

> git add
<br>
Meaning: Addsw file changes to the staging area before committing them.
<br>
Example: git add README.md
<br>
To stage all changes:- git add .
<br>
Use: To select which changes I want to include in the next commit.

> git commit
<br>
Meaning: Saves the staged changes as a commit in the repository's history.
<br>
Example: git commit -m "Add README File"
<br>
Use: To record a meaningful checkpoint in my project.

> git log
<br>
Meaning: Displays the commit history.
<br>
Example: git log
<br>
For a shorter history:- git log --oneline
<br>
Use: To see previous commits and their messages.

> git diff
<br>
Meaning: Shows differences between file versions or changes that have not been staged.
<br>
Example: git diff
<br>
To view staged changes:- git diff --staged
<br>
Use: To review changes before committing.

> git branch
<br>
Meaning: Lists branches in the repository.
<br>
Example: git branch
<br>
To create a new branch:- git branch feature-notes
<br>
Use: To organize work into separate development branches.

> git switch 
<br>
Meaning: Switched to another existing branch.
<br>
Example: git switch feature-notes
<br>
To create and switch to a new branch:- git switch -c feature-readme
<br>
Use: To work on a feature separately from the main branch.

> git merge
<br>
Meaning: Combines changes from one branch into the branch I am currently on.
<br>
Example: git switch main 
<br>
         git merge feature-notes
<br>
Use: To combine completed feature work into another branch, I should merge only when permitted by the project's workflow.

> git push
<br>
Meaning: Uploads the local commits to a remote repository, such as GitHub.
<br>
Example: git push origin main
<br>
Use: To upload the committed changes to GitHub so others can access them.

> git pull
<br>
Meaning: Downloads changes from a remote repository and integrates them into the current local branch.
<br>
Example: git pull origin main
<br> 
Use: To update the local project with changes made by other contributors.

> git fetch
<br>
Meaning: Downloads information about new commits and changes from a remote repository without automatically integrating them into my current branch.
<br>
Example: git fetch origin
<br>
Use: To check for updates on GitHub before deciding whether to integrate them into the local branch.


4. WHAT IS A REPOSITORY?
<br> 
-->A repository is a storage space where your project files and their history are kept. It contains all the versions of your project and helps in version control.
<br>

5. TYPES OF REPOSITORY:
<br>
-->There are two types of repository:-
1) Local Repository - It is stored on your own computer.
<br>
2) Remote Repository - It is stored on a remote server like GitHub, GitLab, etc.
<br> 

5. WHAT IS BRANCHING?
<br>
--> Branching in Git means creating a separate line of development within a repository. It allows developers to work on new features or make changes without directly affecting the main branch.
<br>
Example: If I want to add new information to my README file, I can create a separate branch and work on it independently.
<br>

6. WHY IS BRANCHING IMPORTANT?
<br>
--> It allows multiple developers to work on different features.
<br>
--> It keeps unfinished work separate from the main branch.
<br>
--> It helps organize and manage changes safely.
<br>
--> It makes collaboration easier.

