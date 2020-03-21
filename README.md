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
