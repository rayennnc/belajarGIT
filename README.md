Daftar tugas / branch 
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah GIT
ASUS@rayen MINGW64 ~
$ cd "C:\kuliah\semester 4\pemrogramanweb"

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb
$ git clone https://github.com/rayennnc/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb
$ cd belajarGIT

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ASUS@rayen.(none)')

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-git)
$ git config --global user.email "rayenchris02@gmail.com"

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 25d2713] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-git
Updating 156f2ad..25d2713
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 309 bytes | 154.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rayennnc/belajarGIT.git
   156f2ad..25d2713  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html 4b3312b] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-html
Updating 25d2713..4b3312b
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 112.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rayennnc/belajarGIT.git
   25d2713..4b3312b  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css f96a808] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt
git
ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-css
Updating 4b3312b..f96a808
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 364 bytes | 182.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rayennnc/belajarGIT.git
   4b3312b..f96a808  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js 36e1570] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-js
Updating f96a808..36e1570
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 149.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rayennnc/belajarGIT.git
   f96a808..36e1570  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midProject b4744c5] Menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-midProject
Updating 36e1570..b4744c5
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rayennnc/belajarGIT.git
   36e1570..b4744c5  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 27e1540] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-php
Updating b4744c5..27e1540
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rayennnc/belajarGIT.git
   b4744c5..27e1540  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject e5f93fa] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 27e1540..e5f93fa
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 102.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/rayennnc/belajarGIT.git
   27e1540..e5f93fa  main -> main

ASUS@rayen MINGW64 /c/kuliah/semester 4/pemrogramanweb/belajarGIT (main)
$

