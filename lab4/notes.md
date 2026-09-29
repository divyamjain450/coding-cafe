yQues-1:
--global tells git to aplly this name and email setting across user account on this computer so can be used for all git repositories.
If I leave it out, Git saves the settings locally only for the current repository inside .git/config. You also can't skip it unless you are already inside an initialized Git folder. 

Ques2
The hidden entries ., .., .git, and .venv appeared in ls -a because they start with a dot (.), which ls hides.  The .git directory stores all repository data, configuration settings, commit history.

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

