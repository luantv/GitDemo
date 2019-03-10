This project is just a demo how to use Git

// git init
// git status
// git add
// git commit

// git log   (show log)
// git show  (show detail one commit)
// git diff  (only file modified)

// working directory (Folder working: has files (file has red color))
// staging area      (When commit, files has change at working directory then add into staging area (file has green color))
// git repository    (Save change of commits)

// git checkout -- <file>
// git reset

// git checkout -b <branch> (branching)
// git checkout <branch>
// git merge
A <-- B
git checkout A
git merge B
master <-- feature/dog-class
// git branch -D <branch> (delete a branch)

// git reset --soft <to_comit>  (return status of files commit into staging area (file has green color))
// git reset --mixed <to_comit> (return status of files commit into working directory (file has red color))
// git reset --hard <to_comit>  (delete completed files commit (same discard))

// git revert <comit>

// .gitignore (The purpose is to ignore the files you don't want to commit)

// git config --global credential.helper store
// ^^^ not recommend (~/.git-credentials)
// git config --global credential.helper "cache --timeout=18000"
// google "gnome-keyring" "git ssh" "keychain"

// git clone
// git pull

// Pull request
// 1. git checkout -b <feature-branch>
// 2. git push origin <branch>
// 3. create a pull request on Github
// 4. review code
		4.1 review code online (github)
		4.2 fetch branch into local to test offline (optional)
		4.3 approve to pull request
// 5. merge to master