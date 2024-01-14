Explain version control.

Version control:  Also known as source control or revision control, is a system that manages changes to a set of files over time. Its primary purpose is to track modifications to code, documents, or any other type of files, enabling multiple people to collaborate on a project and keep a record of changes.


Explain difference between git and github

Differences:

Nature:
Git: A distributed version control system installed on a local machine.
GitHub: A web-based platform that hosts Git repositories in the cloud.

Functionality:
Git: Manages version control and tracks changes locally.
GitHub: Provides collaboration tools, remote repository hosting, and social coding features on top of Git.

Location:
Git: Local, installed on a developer's machine.
GitHub: Web-based, accessible through a browser.

Usage:
Git: Used for version control and local development.
GitHub: Used for hosting remote repositories, collaboration, and social coding.


List 3 other github alternatives
a. Gitlab
b. Bitbucket
c. SourceForge


Explain the difference between git fetch and git pull?
git fetch only updates the remote tracking branches without modifying your working directory. It's useful when you want to see what changes are available in the remote repository before deciding to merge.
git pull not only updates the remote tracking branches but also merges the changes into your local branch, updating your working directory. It's a more convenient command if you want to fetch and integrate changes in one step.
Using git fetch allows you to review changes before merging, giving you more control over the merging process.


Explain in simple terms git rebase and the command for it
In simple terms, git rebase is a Git command that helps you modify the history of your changes. It allows you to take the changes from one branch and apply them on top of another branch. This can result in a cleaner and more linear project history compared to traditional merging.
The basic command for git rebase is:
git rebase <branch_name>


Explain in simple terms git cherry-pick and the command for it 
 git cherry-pick is a Git command that allows you to copy a specific commit from one branch and apply it onto another branch. This is useful when you want to pick and choose individual changes from one branch and bring them into another branch without merging the entire branch.
The basic command for git cherry-pick is:
git cherry-pick <commit_hash>