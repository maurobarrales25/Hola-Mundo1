Mauro Barrales

PS C:\Programacion2> git clone https://github.com/maurobarrales25/Hola-Mundo1

PS C:\Programacion2\Hola-Mundo1> git commit -m "Agregando el archivo Readme al Repo"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'bmaur@LAPTOP-RG3JDTML.(none)')
PS C:\Programacion2\Hola-Mundo1> git config --global user.email "bmauro25@gmail.com"
PS C:\Programacion2\Hola-Mundo1> git config --global user.name "Mauro Barrales"
PS C:\Programacion2\Hola-Mundo1> git commit "Agregando el archivo Readme al Repo"
PS C:\Programacion2\Hola-Mundo1> git add Readme
fatal: pathspec 'Readme' did not match any files
PS C:\Programacion2\Hola-Mundo1> git add Readme.md
PS C:\Programacion2\Hola-Mundo1> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Readme.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.md