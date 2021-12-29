# redisson_v2.0
tomcat 9 vers

git push guide
https://corinediary.tistory.com/2

syhwang@DESKTOP-5ERULNP MINGW64 ~/Desktop/syhwang/git/redisson_v2.0 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        redisson-tomcat-9-3.16.1.jar

nothing added to commit but untracked files present (use "git add" to track)

syhwang@DESKTOP-5ERULNP MINGW64 ~/Desktop/syhwang/git/redisson_v2.0 (main)
$ git add redisson-tomcat-9-3.16.1.jar

syhwang@DESKTOP-5ERULNP MINGW64 ~/Desktop/syhwang/git/redisson_v2.0 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   redisson-tomcat-9-3.16.1.jar


syhwang@DESKTOP-5ERULNP MINGW64 ~/Desktop/syhwang/git/redisson_v2.0 (main)
$ git commit -m ["tomcat 9 version"]
[main f865caa] [tomcat 9 version]
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 redisson-tomcat-9-3.16.1.jar

syhwang@DESKTOP-5ERULNP MINGW64 ~/Desktop/syhwang/git/redisson_v2.0 (main)
$ git push origin main
warning: redirecting to https://github.com/Hwang-sangyeon/redisson_v2.0.git/
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 26.63 KiB | 8.88 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To http://github.com/Hwang-sangyeon/redisson_v2.0.git
   905651e..f865caa  main -> main

