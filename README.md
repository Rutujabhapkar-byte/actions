
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

IF ERROR OCURRS:-

ACER@Rutuja MINGW64 ~/actions (main)
$ git pull origin main --allow-unrelated-histories --no-edit

ACER@Rutuja MINGW64 ~/actions (main)
$ git push -u origin main

