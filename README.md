# uliveto(h1)
## sottotitolo(h2)
### sotto-sottotitolo(h3)
...
ciao ale questo è un paragrafo
questo è un elenco numerato:
1. prima
2. seconda
3. terza
ciaoooooooo
..a.a.agi

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ https://github.com/buccialino/uliveto.git
bash: https://github.com/buccialino/uliveto.git: No such file or directory

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ 

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ 

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ 

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ 

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ git config user.name "buccialino"
fatal: not in a git directory

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ cd uliveto

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git config user.name "buccialino"

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$
 *  History restored 


bucci@LAB4-21 MINGW64 ~/Desktop/git
$ cd uliveto

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git config user.name "buccialino"

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git config user.email "buccileon3@gmail.com"

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ ssh-keygen -C "buccileon3@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/bucci/.ssh/id_rsa): 
Created directory '/c/Users/bucci/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/bucci/.ssh/id_rsa
Your public key has been saved in /c/Users/bucci/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:vy6K7OnIdCGYTSxHGcmBU7s+IYRp0nubgEaVl8Qf5Dk buccileon3@gmail.com
The key's randomart image is:
+---[RSA 3072]----+
| +=*+.o.         |
|+==o +...        |
|==* . .E.        |
|=O o   ..        |
|=.B o   S        |
|.o = +   .       |
|  + +     .      |
| o = o  .  .     |
|  oo* .. oo      |
+----[SHA256]-----+

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ cd ..

bucci@LAB4-21 MINGW64 ~/Desktop/git
$ cd ..

bucci@LAB4-21 MINGW64 ~/Desktop
$ cd ..

bucci@LAB4-21 MINGW64 ~
$ pwd
/c/Users/bucci

bucci@LAB4-21 MINGW64 ~
$ .ssh/
bash: .ssh/: Is a directory

bucci@LAB4-21 MINGW64 ~
$ cd .ssh/

bucci@LAB4-21 MINGW64 ~/.ssh
$ ls -al
total 17
drwxr-xr-x 1 bucci 1049089    0 May 24 10:54 ./
drwxr-xr-x 1 bucci 1049089    0 May 24 10:54 ../
-rw-r--r-- 1 bucci 1049089 2610 May 24 10:54 id_rsa
-rw-r--r-- 1 bucci 1049089  574 May 24 10:54 id_rsa.pub

bucci@LAB4-21 MINGW64 ~/.ssh
$ cat id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCyR+aqGswNnQGgXKvgngbBQEMag5fCy/efXABpVYpHitheMywFoar+c1STsu4XUIwxY/TIbOHXYvLyKrmMTJK9Y477pYKoVOF/H8KMiKX1hmZbsR/2NWLaKGSBAyWmNauIJN4S8iiKE01cM2HEB+IRT1AFR3YIpOqOP06/UdagF0Am9R8VX4QwPznXXgfQQFcbyJ9bzBPMBzAi6wdPCMZSOSneUk6D9bGIrrJHkiA3qETXlMbdk05Midmy7er6uvicmwcPWehtm+eSm0FnWz9UmZ+4L9mxZCsfVene/aeGNQUDLADGfhAIWJR/v0nkrUK/AUbbX8260yhgCT6Sz9kbjFw9b60n7rXUw8jBOt5TYX7ijLCsH/QnogEThdPLcbdXAjAfcQpPjy+xXpCR34X6qlUK+R6q/+CyOxtj0xsWXqg6x4WxjGnEGMoBuZxy1TtJkZMEQdp7xHJspUn50tNJY9kL7iKhO1bQuF/Q4ybDUhQ7vq0M9mE+Zv4WgiyzHqk= buccileon3@gmail.com

bucci@LAB4-21 MINGW64 ~/.ssh
$ cd ..

bucci@LAB4-21 MINGW64 ~
$ cd Desktop/git/uliveto

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ pwd
/c/Users/bucci/Desktop/git/uliveto

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pippo.html

no changes added to commit (use "git add" and/or "git commit -a")

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git add 
pippo.html  README.md

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git add README.md

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git add pippo.html

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   pippo.html


bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ pwd
/c/Users/bucci/Desktop/git/uliveto

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git commit -m "Aggiungo e modificato il file"
[main 699aef3] Aggiungo e modificato il file
 2 files changed, 15 insertions(+), 2 deletions(-)
 create mode 100644 pippo.html

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$ git push origin main
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 513 bytes | 513.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/buccialino/uliveto.git
   6110e08..699aef3  main -> main

bucci@LAB4-21 MINGW64 ~/Desktop/git/uliveto (main)
$

faccio iselfie mossi ma aaaa con il  cippalippa nel locale andiamo a comandare