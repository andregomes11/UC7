# UC7-Online

# Códigos usados durante a atividade


MARCELO@DESKTOP-7E1RHFR MINGW64 ~ (master)
$ cd /

$ cd "C:\Users\MARCELO\Documents\_GITUC7"

$ git config user.name
aikawamarcelo

$ git config user.email
aikawamarcelo@gmail.com

$ git init

$ cd UC7-Online/

$ git init

$ git add codigos_atividade.txt

$ git commit -m "adicionando meu primeiro commit."
[master (root-commit) 2bfece8] adicionando meu primeiro commit.
 1 file changed, 28 insertions(+)
 create mode 100644 codigos_atividade.txt

$ git log

commit 2bfece870243e5e0a1b835ffd581091bc8ec0e5c (HEAD -> master)
Author: aikawamarcelo <aikawamarcelo@gmail.com>
Date:   Tue Dec 21 18:00:54 2021 -0300

    adicionando meu primeiro commit.

$ git remote add origin https://github.com/aikawamarcelo/UC7-Online.git

$ git remote -v
origin  https://github.com/aikawamarcelo/UC7-Online.git (fetch)
origin  https://github.com/aikawamarcelo/UC7-Online.git (push)

$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 473 bytes | 94.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/aikawamarcelo/UC7-Online/pull/new/master
remote:
To https://github.com/aikawamarcelo/UC7-Online.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

$ git add codigos_atividade.txt

MARCELO@DESKTOP-7E1RHFR MINGW64 ~/Documents/_GITUC7/UC7-Online (master)
$ git commit -m "adicionando outro arquivo"
[master 98d632b] adicionando outro arquivo
 1 file changed, 54 insertions(+), 28 deletions(-)
 rewrite codigos_atividade.txt (72%)

MARCELO@DESKTOP-7E1RHFR MINGW64 ~/Documents/_GITUC7/UC7-Online (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 923 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/aikawamarcelo/UC7-Online.git
   2bfece8..98d632b  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.


