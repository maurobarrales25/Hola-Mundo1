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
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.md

PS C:\Programacion2\Hola-Mundo1> git add .
PS C:\Programacion2\Hola-Mundo1> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Readme.md

PS C:\Programacion2\Hola-Mundo1> git commit -m "Commit actualizado"
[main 2458943] Commit actualizado
 1 file changed, 36 insertions(+)
 create mode 100644 Readme.md
PS C:\Programacion2\Hola-Mundo1> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Programacion2\Hola-Mundo1> git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 847 bytes | 847.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/maurobarrales25/Hola-Mundo1
   239ea18..2458943  main -> main
PS C:\Programacion2\Hola-Mundo1> 
