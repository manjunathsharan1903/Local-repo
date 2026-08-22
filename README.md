#this is my local repogitgit

PS C:\Users\manju\Documents\Git Demo\LocalRepo> git remote add origin https://github.com/manjunathsharan1903/Local-repo.git
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git remote -v
origin  https://github.com/manjunathsharan1903/Local-repo.git (fetch)
origin  https://github.com/manjunathsharan1903/Local-repo.git (push)
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git branch
* main
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 332 bytes | 332.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/manjunathsharan1903/Local-repo.git
 * [new branch]      main -> main
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git add .
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md

PS C:\Users\manju\Documents\Git Demo\LocalRepo> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\manju\Documents\Git Demo\LocalRepo> git commit -m
error: switch `m' requires a value
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md

PS C:\Users\manju\Documents\Git Demo\LocalRepo> git add .
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git commit -m "adding README.md"
[main 99ee402] adding README.md
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS C:\Users\manju\Documents\Git Demo\LocalRepo> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\manju\Documents\Git Demo\LocalRepo> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/manjunathsharan1903/Local-repo.git
   b4a2332..99ee402  main -> main
PS C:\Users\manju\Documents\Git Demo\LocalRepo> 