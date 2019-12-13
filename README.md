[root@jenkins ~]# cd hello-world/
[root@jenkins hello-world]# ls
Dockerfile  pom.xml  README.md  server  webapp
[root@jenkins hello-world]# cd webapp/
[root@jenkins webapp]# ls
pom.xml  src
[root@jenkins webapp]# cd src/
[root@jenkins src]# ls
main
[root@jenkins src]# cd main/
[root@jenkins main]# cd webapp/
[root@jenkins webapp]# ls
index.jsp  WEB-INF
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
[root@jenkins webapp]# git commit -m "modifikasi file index untuk testing docker menggunakan jenkins & ansible"
[master 70cbdda] modifikasi file index untuk testing docker menggunakan jenkins & ansible
 1 file changed, 1 insertion(+), 1 deletion(-)
[root@jenkins webapp]# git push origin master
Username for 'https://github.com': novanovn
Password for 'https://novanovn@github.com':
Counting objects: 7, done.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 662 bytes | 662.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/novanovn/hello-world.git
   df8dc69..70cbdda  master -> master
