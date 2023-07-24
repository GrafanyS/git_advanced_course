# terminal list

PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git remote -v
origin  https://github.com/GrafanyS/GB_MD.git (fetch)
origin  https://github.com/GrafanyS/GB_MD.git (push)
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git add .
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git commit -m "new .gitignore"
[main 7967c3f] new .gitignore
 1 file changed, 6 insertions(+), 2 deletions(-)
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git remote remove origin      
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git remote -v
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git remote add origin https://github.com/GrafanyS/git_advanced_course.git
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git remote -v
origin  https://github.com/GrafanyS/git_advanced_course.git (fetch)
origin  https://github.com/GrafanyS/git_advanced_course.git (push)
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git push -u origin main
To https://github.com/GrafanyS/git_advanced_course.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/GrafanyS/git_advanced_course.git'      
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git add .
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git commit -m "added link to the new repository https://github.com/GrafanyS/git_advanced_course.git"
On branch main
nothing to commit, working tree clean
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git push -u origin main
To https://github.com/GrafanyS/git_advanced_course.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/GrafanyS/git_advanced_course.git'      
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> gi-help' for details.t push origin +main                                    t push --help
Enumerating objects: 61, done.                         t push origin +main
Counting objects: 100% (61/61), done.
Delta compression using up to 16 threads
Compressing objects: 100% (49/49), done.
Writing objects: 100% (61/61), 1.93 MiB | 1.49 MiB/s, done.                                                   one.
Total 61 (delta 9), reused 53 (delta 6), pack-reused 0 
remote: Resolving deltas: 100% (9/9), done.
To https://github.com/GrafanyS/git_advanced_course.git 
 + 790f357...c9574c0 main -> main (forced update)      
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD>  
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git add .\terminal.md
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git commit -m "terminal list"
[main 89469b8] terminal list
 1 file changed, 53 insertions(+)
 create mode 100644 terminal.md
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD> git push --set-upstream origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.17 KiB | 1.17 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GrafanyS/git_advanced_course.git
   c9574c0..89469b8  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\ServerGrafany\Desktop\GIT_SEMINAR\GB_MD>
