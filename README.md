# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT

nasya@Nasya-PC MINGW64 ~ (master)
$ cd Desktop
bash: cd: Desktop: No such file or directory

nasya@Nasya-PC MINGW64 ~ (master)
$ l
bash: l: command not found

nasya@Nasya-PC MINGW64 ~ (master)
$ l
bash: l: command not found

nasya@Nasya-PC MINGW64 ~ (master)
$ ls
 AppData/
'Application Data'@
'CbA02 - DOV (1).zip'
'CbA02 - DOV (2).zip'
'CbA02 - DOV.zip'
 CbA04.ipynb
 Contacts/
 Cookies@
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 LABTBD1.sql
 LABTBD11.sql
 LABTBD2.sql
 LABTBD21.sql
 LABTBD22.sql
 LABTBD23.sql
 LABTBD24.sql
 Links/
'Local Settings'@
 Music/
'My Documents'@
'My project'/
'My project (1)'/
'My project (2)'/
'My project (3)'/
 NTUSER.DAT
 NTUSER.DAT{621b4445-77f5-11ed-b67f-f8a6ecadd22a}.TM.blf
 NTUSER.DAT{621b4445-77f5-11ed-b67f-f8a6ecadd22a}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{621b4445-77f5-11ed-b67f-f8a6ecadd22a}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
'New folder'/
 OneDrive/
 Oracle/
 PrintHood@
 Recent@
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Tugasmandir1i.cpp
 Tugasmandir1i.exe*
 Tugasmandiri.cpp
'Untitled Folder'/
'Untitled Folder 1'/
'Untitled Folder 2'/
 Untitled.ipynb
 Videos/
 anaconda/
 anaconda3/
 cd
 composer.phar*
 log_praktikum/
 log_praktikum_modul1_NasyaEmanuelSoekamto.log
 logs/
'modul 4'/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 sqlplus
 tempCodeRunnerFile.cpp

nasya@Nasya-PC MINGW64 ~ (master)
$ cd Documents

nasya@Nasya-PC MINGW64 ~/Documents (master)
$ git clone https://github.com/Nasya030205/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

nasya@Nasya-PC MINGW64 ~/Documents (master)
$ ls
'My Music'@  'My Pictures'@  'My Videos'@   belajarGIT/

nasya@Nasya-PC MINGW64 ~/Documents (master)
$ git branch

nasya@Nasya-PC MINGW64 ~/Documents (master)
$ git branch Tugas-git
fatal: not a valid object name: 'master'

nasya@Nasya-PC MINGW64 ~/Documents (master)
$ pwd
/c/Users/nasya/Documents

nasya@Nasya-PC MINGW64 ~/Documents (master)
$ cd belajarGIT

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-git
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ ls
README.md

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout -b Tugas-git
fatal: a branch named 'Tugas-git' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ echo. > Tugas-git.txt
bash: echo.: command not found

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 8dca3ec] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-git.txt

no changes added to commit (use "git add" and/or "git commit -a")

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan yang ada pada staging area"
[Tugas-git 333cc01] Menambahkan perubahan yang ada pada staging area
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git branch
* Tugas-git
  main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git pull origin main
From https://github.com/Nasya030205/belajarGIT
 * branch            main       -> FETCH_HEAD
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 1ed66f5..333cc01
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Merge branch 'Tugas-Git' into main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 571 bytes | 285.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Nasya030205/belajarGIT.git
   1ed66f5..333cc01  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ ^C

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ ^C

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$  ^C


nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd Documents
bash: cd: Documents: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-git
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ ^C

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b TUgas-html
fatal: a branch named 'TUgas-html' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ ls
README.md  Tugas-git.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-html
fatal: a branch named 'Tugas-html' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-html.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-html.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-html.txt"
[main b537eb5] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-html.txt

no changes added to commit (use "git add" and/or "git commit -a")

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-html.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan pada Tugas-html.txt"
[main 235c570] Menambahkan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 550 bytes | 183.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Nasya030205/belajarGIT.git
   333cc01..235c570  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ ^[[200~cd Documents
bash: $'\E[200~cd': command not found

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd Documents
bash: cd: Documents: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-css
fatal: a branch named 'Tugas-css' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-css.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-css.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "menambahkan file Tugas-css.txt"
[main 3be1824] menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-css.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[main ae68dce] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 594 bytes | 297.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Nasya030205/belajarGIT.git
   235c570..ae68dce  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd Documents
bash: cd: Documents: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-js
fatal: a branch named 'Tugas-js' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[main 933d243] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[main 05be707] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-js
fatal: a branch named 'Tugas-js' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-js.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-js.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[main e86de79] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 786 bytes | 196.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/Nasya030205/belajarGIT.git
   ae68dce..e86de79  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-midProject
fatal: a branch named 'Tugas-midProject' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-midProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-midProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[main 2fdf689] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-midProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[main acaf330] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 551 bytes | 183.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Nasya030205/belajarGIT.git
   e86de79..acaf330  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-php
fatal: a branch named 'Tugas-php' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-php.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-php.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambah file Tugas-php.txt"
[main 10abfcb] Menambah file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-php.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[main f8cda20] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 526 bytes | 175.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Nasya030205/belajarGIT.git
   acaf330..f8cda20  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cdbelajarGIT
bash: cdbelajarGIT: command not found

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout -b Tugas-finalProject
fatal: a branch named 'Tugas-finalProject' already exists

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ touch Tugas-finalProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-finalProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[main 7d5450d] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git add Tugas-finalProject.txt

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[main faae79b] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
fatal: unable to access 'https://github.com/Nasya030205/belajarGIT.git/': Could not resolve host: github.com

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Already up to date.

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 541 bytes | 135.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Nasya030205/belajarGIT.git
   f8cda20..faae79b  main -> main

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-finalProject
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-finalProject' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-finalProject
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-finalProject -> Tugas-finalProject

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-git
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-git' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-git
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-git -> Tugas-git

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-html
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-html' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-html
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-html -> Tugas-html

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-css
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-css' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-css
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-css -> Tugas-css

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-js
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-js' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-js
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-js -> Tugas-js

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-midProject
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-midProject' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-midProject
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-midProject -> Tugas-midProject

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-php
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-php' on GitHub by visiting:
remote:      https://github.com/Nasya030205/belajarGIT/pull/new/Tugas-php
remote:
To https://github.com/Nasya030205/belajarGIT.git
 * [new branch]      Tugas-php -> Tugas-php

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-finalProject
Everything up-to-date

nasya@Nasya-PC MINGW64 ~/Documents/belajarGIT (main)
$
