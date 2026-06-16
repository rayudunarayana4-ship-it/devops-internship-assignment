
# DevOps Internship Assignment

## Part 1: Git & SSH

### Difference between git fetch and git pull

Git Fetch:

Git fetch downloads the latest changes from the remote repository to your local repository. It updates the remote tracking branches but does not merge the changes into your current branch.

Command:

git fetch


Git Pull:

Git pull downloads the latest changes from the remote repository and automatically merges them into your current branch.

It is equivalent to running:

git fetch
git merge

Command:

git pull


Key Difference:

Git Fetch:
- Downloads changes only
- Does not modify your current branch
- Allows you to review changes before merging

Git Pull:
- Downloads and merges changes automatically
- Updates your current branch immediately
- Faster because everything happens in a single command

 Feature A and Feature B changes resolved
