>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


**Learnable25-26**

# version control.

Version control, or source control, is an online software development platform that is used for storing, tracking, and manages changes on software projects. It allows developers to collaborate, revert to previous states, and maintain a history of modifications, acting as a "time machine" for projects.

## Difference between git and github

Git is a local, open-source version control system (VCS), while GitHub is a cloud-based platform that hosts Git repositories and facilitates collaboration.

Git: is the tool you use on your computer to track changes in your code, manage different versions, and work offline.

GitHub : is a website (a "hub") where you can store your Git projects online, share them with others, and use additional tools for teamwork like issue tracking and code reviews.

## github alternatives

1. Apache Subversion (SVN)
2. Mercurial (Hg)
3. Fossil

## Difference between git fetch and git pull

Git fetch: only downloads remote changes to your local repository.
Use Case: Ideal for checking for updates, reviewing changes, or backing up work without disrupting your current work.

Git pull: downloads and automatically merges those changes into your current working branch (branch).
Use Case: Best for quickly synchronizing your local branch with the remote when you are sure there won't be conflicts.

## git rebase and it's command

git rebase is a command that integrates changes from one Git branch into another by moving your current branch's commits on top of the target branch's latest commits(e.g main). The primary goal is to create a cleaner, linear project history, avoiding the extra "merge commits" that result from a standard git merge

command: let assume i have a branch called feature/dasboard and i want to merge all the commit in this branch to main, then i use the below commad:
git rebase main

## git cherry-pick and it's command

Cherry picking is the act of picking a commit from a branch and applying it to another. git cherry-pick can be useful for undoing changes. For example, say a commit is accidently made to the wrong branch. You can switch to the correct branch and cherry-pick the commit to where it should belong.
command : git cherry-pick commit-hash
