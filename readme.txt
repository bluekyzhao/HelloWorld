git init

git add xxxxx
git commit -m ""

git status
git diff

git log
git reset -hard id
git reflog

git checkout -- file  //工作区修改删除
git reset HEAD file   //暂存区回退到工作区

git rm file
git commit -m ""

git branch
git branch <name>
git checkout <name>
git checkout -b <name>
git merge <name>
git branch -d <name>
git push origin :branch-name   //删除远程分支


ssh-keygen -t rsa -C "youremail@example.com"
登陆GitHub，打开“Account settings”，“SSH Keys”页面：
然后，点“Add SSH Key”，填上任意Title，在Key文本框里粘贴id_rsa.pub文件的内容

要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；