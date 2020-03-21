# alexcami.github.io

/alexcami.github.io $ echo "# alexcami.github.io" >> README.md
/alexcami.github.io $ git init
Initialized empty Git repository in /home/pi/AC/alexcami.github.io/.git/
pi@rpiac:~/AC/alexcami.github.io $ git init
Reinitialized existing Git repository in /home/pi/AC/alexcami.github.io/.git/
/alexcami.github.io $ git add README.md
/alexcami.github.io $ git config --global user.name alexcami
/alexcami.github.io $ git config --global user.email alexcami@gmail.com
/alexcami.github.io $ git commit -m "first commit"
[master (root-commit) 0247b08] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
pi@rpiac:~/AC/alexcami.github.io $ git remote add origin https://github.com/alexcami/alexcami.github.io.git
pi@rpiac:~/AC/alexcami.github.io $ git push -u origin master
Username for 'https://github.com': alexcami
Password for 'https://alexcami@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 228 bytes | 28.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/alexcami/alexcami.github.io.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.


/alexcami.github.io $ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

pi@rpiac:~/AC/alexcami.github.io $ git add README.md 
pi@rpiac:~/AC/alexcami.github.io $ git commit -m "edit README.md"
[master 95142ae] edit README.md
 1 file changed, 24 insertions(+)
/alexcami.github.io $ git push
Username for 'https://github.com': alexcami
Password for 'https://alexcami@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 715 bytes | 102.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/alexcami/alexcami.github.io.git
   0247b08..95142ae  master -> master
/alexcami.github.io $ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

