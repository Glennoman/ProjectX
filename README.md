Geo@DESKTOP-LI44A1N MINGW64 ~/development (main)
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~
$ mkdir ProjectX

Geo@DESKTOP-LI44A1N MINGW64 ~
$ cd ProjectX/

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ mkdir docs

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ cd docs

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ mdir reports
bash: mdir: command not found

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ mkdir reports

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ cd reports

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs/reports
$ touch report_one.txt

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs/reports
$ touch report_two.txt

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs/reports
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ mkdir images

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ mkdir src

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ cd src

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ mkdir html

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ touch index.html

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ rm index.html

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ cd html

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/html
$ touch index.html

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/html
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ mkdir css

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ cd css

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/css
$ touch style.css

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/css
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ mkdir js

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ cd js

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/js
$ touch script.js

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/js
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ mkdir data

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ cd data

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/data
$ touch data.txt

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/data
$ echo "Hello Data" >> data.txt

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src/data
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/src
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ git push
fatal: not a git repository (or any of the parent directories): .git

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ git push
fatal: not a git repository (or any of the parent directories): .git

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ cd docs

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ cd images

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs/images
$ touch bonus.gitkeep

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs/images
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX/docs
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX
$ git init
Initialized empty Git repository in C:/Users/Geo/ProjectX/.git/

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git add .
warning: in the working copy of 'src/data/data.txt', LF will be replaced by CRLF the next time Git touches it

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git commit -m "initial setup"
[master (root-commit) 761683e] initial setup
 7 files changed, 1 insertion(+)
 create mode 100644 docs/images/bonus.gitkeep
 create mode 100644 docs/reports/report_one.txt
 create mode 100644 docs/reports/report_two.txt
 create mode 100644 src/css/style.css
 create mode 100644 src/data/data.txt
 create mode 100644 src/html/index.html
 create mode 100644 src/js/script.js

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git remote add origin git@github.com:Glennoman/ProjectX.git

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Glennoman/ProjectX.git'

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git remote add origin https://github.com/Glennoman/ProjectX.git
error: remote origin already exists.

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Glennoman/ProjectX.git'

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git fetch origin
Enter passphrase for key '/c/Users/Geo/.ssh/id_ed25519':
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.73 KiB | 177.00 KiB/s, done.
From github.com:Glennoman/ProjectX
 * [new branch]      main       -> origin/main

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git merge origin/main
fatal: refusing to merge unrelated histories

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git pull
Enter passphrase for key '/c/Users/Geo/.ssh/id_ed25519':
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master


Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git pull (1)
bash: syntax error near unexpected token `('

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git branch
* master

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ git push -f origin main
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Glennoman/ProjectX.git'

Geo@DESKTOP-LI44A1N MINGW64 ~/ProjectX (master)
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~
$ cd development/

Geo@DESKTOP-LI44A1N MINGW64 ~/development (main)
$ ls
Prep-Work-Project/  ProjectX/  resourcify-/  vscode-prework-exercise/

Geo@DESKTOP-LI44A1N MINGW64 ~/development (main)
$ cd ProjectX/

Geo@DESKTOP-LI44A1N MINGW64 ~/development/ProjectX (master)
$ git remote add origin https://github.com/Glennoman/ProjectX.git
error: remote origin already exists.

Geo@DESKTOP-LI44A1N MINGW64 ~/development/ProjectX (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Glennoman/ProjectX.git'

Geo@DESKTOP-LI44A1N MINGW64 ~/development/ProjectX (master)
$ cd ..

Geo@DESKTOP-LI44A1N MINGW64 ~/development (main)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

Geo@DESKTOP-LI44A1N MINGW64 ~/development (main)
$ git push
Everything up-to-date
