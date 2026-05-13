# Gym-Git-Exercise-Solutions

## Bundle 1 

### Exercise 1 

```bash
LENOVO@Steven MINGW64 /
$ cd Git Exercises
bash: cd: too many arguments

LENOVO@Steven MINGW64 /
$ cd "Git Exercises"
bash: cd: Git Exercises: No such file or directory

LENOVO@Steven MINGW64 /
$ cd c:/Users/LENOVE/Downloads/Git_Exercises
bash: cd: c:/Users/LENOVE/Downloads/Git_Exercises: No such file or directory

LENOVO@Steven MINGW64 /
$ cd c:/Users/LENOVO/Desktop/Git_Exercises

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises
$ git init
Initialized empty Git repository in C:/Users/LENOVO/Desktop/Git_Exercises/.git/

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (master)
$ git branch

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (master)
$ git branch -m main

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git add README.md

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git commit -m "init project"
[main (root-commit) 062a3a7] init project
 1 file changed, 5 insertions(+)
 create mode 100644 README.md

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git remote add origin https://github.com/sntwali2003/git-exercise.git

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git status
On branch main
nothing to commit, working tree clean

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$  git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 254 bytes | 127.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/sntwali2003/git-exercise.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git push
Everything up-to-date

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (main)
$ git checkout -b dev
Switched to a new branch 'dev'

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/sntwali2003/git-exercise/pull/new/dev
remote:
To https://github.com/sntwali2003/git-exercise.git
 * [new branch]      dev -> dev

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (dev)
$ git checkout -b test
Switched to a new branch 'test'

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/sntwali2003/git-exercise/pull/new/test
remote:
To https://github.com/sntwali2003/git-exercise.git
 * [new branch]      test -> test

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (test)
$ git checkout dev
Switched to branch 'dev'

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (dev)
$ git branch -D test
Deleted branch test (was 062a3a7).

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (dev)
$ git push origin --delete test
To https://github.com/sntwali2003/git-exercise.git
 - [deleted]         test

LENOVO@Steven MINGW64 ~/Desktop/Git_Exercises (dev)
$
```
