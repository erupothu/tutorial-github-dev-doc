
* create folder(harishe-techie) and project files (ex: home.html, about.html, contact.html)
* create git project
  * `git init`
  * `git status` (show status about files to add, conficts, commits etc)
  * Commint the files
    * `git commit -m "initial commit"`
  * Check Logs
    * `git log`
    * `git log --pretty=full`
    * `git log --onlineline`
    * git log --online --all
    * git log --online --graph --all
  * Create branch (Branching)
    * `git branch brandh-101`
    * `git checkout -b branch-102` (create and switch to new branch)
  * Switch to branch-101 branch
    * `git checkout branch-101`
    * Create new files and update files fetched from master and commit (ex: create media.html)
    * `git commit -m "media.html added"`
  * Merge sub branch data to master branch
    * `git checkout master` (switch to master branch)
    * `git merge branch-101` (merge media.html file from branch-101 to master branch)
  * Delete Branch
    * `git branch -d branch-101`
  * Merge Conflicts
    * `git branch --merge` (merged brnahces)
    * `git branch --no-merge` (pending branches to merge)
    * `git branch -a (show all branches)
    * `git checkout branch-102`
    * `git commit -m "updated about.hmtl"` (updating about.html in branch-102)
    * `git checkout master'
    * `git merge branch-102` (conflict in about.html)
    *  `nano about.html` (remove conflicting data commented with <<<<<<< current data ======= merging branch changes >>>>>>>)
    *  `git add about.html`
    *  `git commit -m 'updated with current data"`
    *  `git status`
  *  Remote Branching (GitHub, GitLab, code commit)
  *  `git clone https://remote-git-project-url` 
  *  `git remote` 
  *  `git commit -m "updated home page"` (update remote file in local repo)
  *  `git log --online --all --graph` (show local commited files logs)
  *  `git fetch orign` (fetch changes from remote server to origin master)
  *  `git branch -a`
  *  `git merge origin/master` (merge remote chanes to local)
  *  'git pull origin master` (directly pull changes from remote to local)
  *  `git push origin master`
