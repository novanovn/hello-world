# maven-project

Simple Maven Project


#Test update

[root@jenkins webapp]# vi index.jsp
[root@jenkins webapp]# git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   index.jsp

no changes added to commit (use "git add" and/or "git commit -a")
[root@jenkins webapp]# git add .
[root@jenkins webapp]# git commit -m "modified index.jsp"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'root@jenkins.(none)')
[root@jenkins webapp]# git config --global user.email novanovn@gmail.com
[root@jenkins webapp]# git config --global user.name novan hariman
[root@jenkins webapp]# git commit -m "modified index.jsp"
[master 326801d] modified index.jsp
 1 file changed, 1 insertion(+), 1 deletion(-)
[root@jenkins webapp]# git push origin master
Username for 'https://github.com': novanovn
Password for 'https://novanovn@github.com':
Counting objects: 7, done.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 596 bytes | 596.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/novanovn/hello-world.git
   e023267..326801d  master -> master
[root@jenkins webapp]# git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
