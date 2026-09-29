yQues-1:
--global tells git to aplly this name and email setting across user account on this computer so can be used for all git repositories.
If I leave it out, Git saves the settings locally only for the current repository inside .git/config. You also can't skip it unless you are already inside an initialized Git folder. 

Ques2The hidden entries ., .., .git, and .venv appeared in ls -a because they start with a dot (.), which ls hides.  The .git directory stores all repository data, configuration settings, commit history.

Ques-3
Git is attempting to track about 5 items/folders (README.md, lab4, myenv, week01, week02) and the hidden ones too. The .venv or myenv virtual environment folder is noteworthy since it holds code I didn't write, with thousands of third-party library files.

Ques-4
When i run git status again .venv/ is no longer listed while .gitignore appears as untracked file .

Ques-5
yes, .gitignore should be comitted so that all collaborators share same rules for ignoring unwanted file in repository.

Ques-6
README.md moved from untracked files to changes to be commited. In a three places model running git add moved the file from the Working Directory into the Staging Area

Ques-7
Git printed the[master (root-commit) 7a93cf3] Lab work so far
 6 files changed, 174 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 lab4/notes.md
 create mode 100644 notes,md
 create mode 100644 week02/lab01-log.txt
 create mode 100644 week02/notes.md
and it says i changed file 6 times.

Ques-8
The first seven characters are called the short commit hash(7a93cf3). They are as unique id to identify specific commit in git history.

Ques-9
The four steps of the Git loop are:
1. Edit/Modify 
2. Check status 
3. Stage (to add file)
4. Commit
ques-10
READMEmd is special because GitHub automatically renders it as the front page of your repository. Leaving it in the main folder means that anyone who opens your project can immediately see what the project is about and how it works.
Ques-11
gh auth login authenticates your machine using an OAuth security token stored locally by the GitHub. This token acts as a persistent credential, allowing Git to verify your identity on future pushes without prompting for your password.
Ques-12
README is shown automatically on the repository front page.md right below the file list. GitHub is meant to specifically look for a root README.md file and show that as the main landing page for anyone coming to the project.

Ques-13
No, running git push did not change local commit history. It simply uploaded the local commits to the remote GitHub repository so that both the local and remote histories match.

Ques-14
A private repository exists on GitHub with all its files and history, but access is restricted so only authorized collaborators can view it. A repository that does not exist at all has no files, history, or remote record stored on GitHub
