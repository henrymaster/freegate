# freegate

第一步 检出仓库
$ git clone /path/to/repository

第二步 添加与提交
$ git add <filename>
$ git commit -m "代码提交信息"

第三步 推送改动
$ git push origin master

更新与合并
$ git pull

Generating a new SSH key
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

git log
git reflog
git reset <id>

替换本地改动
git checkout -- <filename>

到服务器上获取最新的版本并将你本地主分支指向到它
git fetch origin
git reset --hard origin/master
