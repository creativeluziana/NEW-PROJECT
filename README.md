PS C:\Users\admin\Desktop\GIT123> git init
Reinitialized existing Git repository in C:/Users/admin/Desktop/GIT123/.git/
PS C:\Users\admin\Desktop\GIT123> git commit -m "first commit"
On branch main
nothing to commit, working tree clean
PS C:\Users\admin\Desktop\GIT123> git . add
git: '.' is not a git command. See 'git --help'.

        mv
        rm
PS C:\Users\admin\Desktop\GIT123> git add .
PS C:\Users\admin\Desktop\GIT123> git remote -v
origin  https://github.com/creativeluziana/SE-11 (push)
PS C:\Users\admin\Desktop\GIT123> git remote add dev https://github.com/creativeluziana/NEW-PROJECT.git       
error: remote dev already exists.
PS C:\Users\admin\Desktop\GIT123> git remote add dev https://github.com/creativeluziana/NEW-PROJECT.git       
error: remote dev already exists.
PS C:\Users\admin\Desktop\GIT123> git remote add origin https://github.com/creativeluziana/NEW-PROJECT.git    
PS C:\Users\admin\Desktop\GIT123> git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 605 bytes | 302.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/creativeluziana/NEW-PROJECT.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\admin\Desktop\GIT123> 
