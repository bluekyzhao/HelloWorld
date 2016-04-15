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


ssh-keygen -t rsa -C "youremail@example.com"
登陆GitHub，打开“Account settings”，“SSH Keys”页面：
然后，点“Add SSH Key”，填上任意Title，在Key文本框里粘贴id_rsa.pub文件的内容