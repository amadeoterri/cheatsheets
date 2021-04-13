<h1 style="text-align:center;">
CHEATSHEAT FOR GIT
</h1>
<h4> Standard </h4>

| Command                                                          |                                    Explained                                     |
| ---------------------------------------------------------------- | :------------------------------------------------------------------------------: |
| git config -l                                                    |                            check user email and name                             |
| git config --global user.email &lt;EMAIL&gt;                     |                                  set user email                                  |
| git config --global user.email &lt;NAME&gt;                      |                                  set user name                                   |
| git clone &lt;URL&gt;                                            |    clone project from remote project (insert &lt;URL&gt;) into current folder    |
| git init                                                         |                              start a new local repo                              |
| git status                                                       |          which local files/directories are added, adjusted or untracked          |
| git add .                                                        | adds a change in the working directory to the staging area, these are the files/ |
| git add -A                                                       |                        directories that will be commited                         |
| git add &lt;FILE/DIRECTORY&gt;                                   |                                                                                  |
| git commit -m "&lt;MESSAGE&gt;"                                  |         commit (staged files) to your local repo with a &lt;MESSAGE&gt;          |
| git commit -a -m "&lt;MESSAGE&gt;"                               |                          commit and add unstaged files                           |
| git remote add &lt;REMOTE_NAME&gt; &lt;REMOTE URL&gt;            |                add new remote (f.e. origin) to &lt;REMOTE URL&gt;                |
| git remote set-url &lt;REMOTE_NAME&gt; &lt;REMOTE URL&gt;        |         change existing remote &lt;REMOTE_NAME&gt; to &lt;REMOTE URL&gt;         |
| git push -u orgin &lt;BRANCH_NAME&gt;                            |              pushes changes that you staged on &lt;BRANCH_NAME&gt;               |
| git remote -v                                                    |                         see all the names of the remote                          |
| git branch &lt;BRANCH_NAME&gt;                                   |                                make a new branch                                 |
| git branch                                                       |                                 see all branches                                 |
| git branch -d &lt;BRANCH_NAME&gt;                                |                        remove branch &lt;BRANCH_NAME&gt;                         |
| git checkout &lt;BRANCH_NAME&gt;                                 |                            go to &lt;BRANCH_NAME&gt;                             |
| git merge &lt;BRANCH_NAME&gt;                                    |                  merge current branch with &lt;BRANCH_NAME&gt;                   |
| git checkout -b &lt;BRANCH_NAME&gt;                              |                          make a new branch and checkout                          |
| git pull                                                         |                                   pull changes                                   |
| git pull origin main                                             |               update local 'origin' repo from remote 'main' branch               |
| git checkout -b &lt;MY_BRANCH_NAME&gt; &lt;OTHER_BRANCH_NAME&gt; |    checkout from other branch to new mybranch (-b means 'create new branch')     |
| git revert &lt;COMMIT&gt;                                        |                                 commit reverten                                  |
| git fetch                                                        |     repo bijwerken met laatste status van de server, maar gaat niet working      |
|                                                                  |    directory aanpassen, daarna doe j een git merge om ze effectief binnen te     |
|                                                                  |                                      halen                                       |
| git switch -c &lt;NEW_BRANCH&gt;                                 |                       create a new branch and switch to it                       |
| git log --oneline                                                |                                 log all commits                                  |
| git mv &lt;DIRECTORY_OR_FILE&gt; &lt;DIRECTORY&gt;               |                   move file or directory to another directory                    |
