hello world
this is my first study git!
git add "fileName"
git status
git commit -m"remark"

#要关联一个远程库
git remote add origin git@server-name:path/repo-name.git

#first push
git push -u origin master

#push
git push origin master

#查看分支
git branch
#创建分支
git branch <name>
#切换分支
git checkout <name>
#创建+切换分支
git checkout -b <name>
#合并某分支到当前分支
git merge <name>
#删除分支
git branch -d <name>
#强行删除分支
git branch -D <name>
#查看远程库信息
git remote -v
#push到远程
git push origin <name>
#pull到本地
git pull
#指定本地分支和远程分支得链接
git branch --set-upstream-to=origin/<name> <name>
