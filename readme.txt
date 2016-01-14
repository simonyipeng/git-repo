-git install history

#wget https://github.com/git/git/archive/v2.2.0.tar.gz

#tar -zxvf v2.2.0.tar.gz


#yum install curl-devel
#yum install expat-devel
#yum install gettext-devel zlib-devel
#yum install openssl-devel
#yum install perl-devel

#make perfix=/usr/local all
#sudo make prefix=/usr/local install




#init a user --> root

#  git config --global user.email "you@example.com"
#  git config --global user.name "Your Name"
git config --global user.email "root@xxmserver.com"
git config --global user.name "root"


#git status
#git status -- observe the git working dictionary's status

#git diff
#git diff -- allow you observe the different of two version (current & the lasted committed)

#git log
#git log -- scan all the version update history 

#git reset
#git reset -- git reset with HEAD , which coule help you to rollback to the appointed commit version.
#example:
#git reset --hard HEAD^  -- rollback to last version.
#git reset --hard HEAD^^  -- rollback to the last of last version.

#git reflog
#git reflog -- log list of all you commited command.

#git logs direction location
# .git/logs/refs/heads , in it git saved all the history record of version exchange.

#git checkout -- filename
#git checkout could drop all of your modification from last commit

#git reset HEAD filename
#git reset HEAD means unstage to last version


#rm                      --> delete from local disk
#git rm                  --> delete from local disk and stage
#git reset --head HEAD^  --> recover master from recycle bin.
#git reset HEAD -- file  --> recover from master to stage
#git checkout -- file    --> recover from stage to local file
