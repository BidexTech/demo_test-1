# demo1

Home@Home-PC MINGW64 ~
$ cd downloads

Home@Home-PC MINGW64 ~/downloads
$ cd demo_test

Home@Home-PC MINGW64 ~/downloads/demo_test (main)
$ cd

Home@Home-PC MINGW64 ~
$ cd downloads

Home@Home-PC MINGW64 ~/downloads
$ mkdir demo_test1

Home@Home-PC MINGW64 ~/downloads
$ cd demo_test1

Home@Home-PC MINGW64 ~/downloads/demo_test1
$ echo "# demo1" >> README.md

Home@Home-PC MINGW64 ~/downloads/demo_test1
$ git init
Initialized empty Git repository in C:/Users/Home/Downloads/demo_test1/.git/

Home@Home-PC MINGW64 ~/downloads/demo_test1 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the nex
t time Git touches it

Home@Home-PC MINGW64 ~/downloads/demo_test1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


Home@Home-PC MINGW64 ~/downloads/demo_test1 (master)
$ git commit -m "first commit"
[master (root-commit) 9bc2b07] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Home@Home-PC MINGW64 ~/downloads/demo_test1 (master)
$ git remote add origin git@github.com:BidexTech/demo_test-1.git

Home@Home-PC MINGW64 ~/downloads/demo_test1 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 229 bytes | 114.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:BidexTech/demo_test-1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Home@Home-PC MINGW64 ~/downloads/demo_test1 (master)
