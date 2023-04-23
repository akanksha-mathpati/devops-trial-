# devops-trial-
trial


amath@LAPTOP-HI6TV43M MINGW64 ~/devops (main)
$ mkdir practical

amath@LAPTOP-HI6TV43M MINGW64 ~/devops (main)
$ cd practical

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ echo "#hi" >> first.html

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git init
Initialized empty Git repository in C:/Users/amath/devops/practical/.git/

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git add first.html
warning: in the working copy of 'first.html', LF will be replaced by CRLF the next time Git touches it

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git commit -m "hg"
[main (root-commit) 98cd737] hg
 1 file changed, 1 insertion(+)
 create mode 100644 first.html

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git remote

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git remote add origin https://github.com/akanksha-mathpati/devops-trial-.git

amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git push -u origin
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


amath@LAPTOP-HI6TV43M MINGW64 ~/devops/practical (main)
$ git push -u origin main
$ git pull -u origin main 
