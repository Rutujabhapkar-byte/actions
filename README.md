
ACER@Rutuja MINGW64 ~
$ mkdir actions

ACER@Rutuja MINGW64 ~
$ cd actions

ACER@Rutuja MINGW64 ~/actions
$ nano hello.py

ACER@Rutuja MINGW64 ~/actions
$ cat hello.py 

output:-print ("hello world!")
print("welcome to github actions")


ACER@Rutuja MINGW64 ~/actions
$ mkdir -p .github/workflows


ACER@Rutuja MINGW64 ~/actions
$ nano .github/workflows/basic-commands.yml

ACER@Rutuja MINGW64 ~/actions
$ ls -R
.: output:-
hello.py

ACER@Rutuja MINGW64 ~/actions
$ git init 
output:-
Initialized empty Git repository in C:/Users/ACER/actions/.git/

ACER@Rutuja MINGW64 ~/actions (main)
$ git add .

ACER@Rutuja MINGW64 ~/actions (main)
$ git commit -m "first actions"


ACER@Rutuja MINGW64 ~/actions (main)
$ git branch -M main

ACER@Rutuja MINGW64 ~/actions (main)
$ git remote add origin https://github.com/Rutujabhapkar-byte/actions.git


ACER@Rutuja MINGW64 ~/actions (main)
$ git push -u origin main
To https://github.com/Rutujabhapkar-byte/actions.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Rutujabhapkar-byte/actions.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

ACER@Rutuja MINGW64 ~/actions (main)
$ git pull origin main --allow-unrelated-histories --no-edit

remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 856 bytes | 34.00 KiB/s, done.
From https://github.com/Rutujabhapkar-byte/actions
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

ACER@Rutuja MINGW64 ~/actions (main)
$ git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 977 bytes | 195.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Rutujabhapkar-byte/actions.git
   c425ced..9e4f476  main -> main
branch 'main' set up to track 'origin/main'.
