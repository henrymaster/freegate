
第一步 检出仓库 <br>
$ git clone /path/to/repository <br>

第二步 添加与提交 <br>
$ git add <filename> <br>
$ git commit -m "代码提交信息" <br>

第三步 推送改动 <br>
$ git push origin master <br>

更新与合并 <br>
$ git pull <br>

Generating a new SSH key <br>
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com" <br>

git log <br>
git reflog <br>
git reset <id> <br>

替换本地改动 <br>
git checkout -- <filename> <br>

到服务器上获取最新的版本并将你本地主分支指向到它 <br>
git fetch origin <br>
git reset --hard origin/master <br>
