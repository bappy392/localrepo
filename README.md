
Git status there have type
Untracked – new files that git doesn’t yet track
Modified – changed
Staged – file is ready to be committed 
Unmodified – unchanged

================================
Initial git
================================
git init
git remote add origin <link>
git remote -v  (to verify remote)
git branch (to check branch)
git branch -M main (to rename branch)
git push origin main

======================================
Branch Commands
======================================
git branch (to check branch)
git branch -M main (to rename branch)
git checkout <branch name>   (to navigate)
git checkout -b <new branch name> (to create new branch)
git branch -d <branch name>   (to delete branch)

=================================
Merging Code
=================================
Way 1
git diff <branch name>  (to compare commits, branches, files & more)
git merge <branch name>  (to merge 2 branch>

way 2
Create a PR into web

=======================
Pull Command
=======================
git pull origin main
git pull -u origin main  (-u set one time origin main not need repeated just could use git pull only)

=========================
Resolving Merge Conflicts
=========================
git diff main
git merge main
Accept current change  |  Accept incoming change | Accept Both Changes
Then 
git add .
git commit and push

==========================
Undoing Changes
==========================
Case 1: staged changes
git reset <file name>  or git reset   (for all)

Case 2: committed changes (for one commit)
git reset HEAD~1  (current one commit reset)

Case 3: committed changes (for many commits)
git reset      <commit hash>
git reset - -hard  <commit hash>

========================
Fork
====================
A fork is a new repository that shares code and visibility settings with the original “upstream” repository. Fork is a rough copy.

