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
git branch --set-upstream-to <branch-name> origin/<branch-name>
#多人协作的技巧
#1.在本地创建和远程分支对应的分支
git checkout -b <branch-name> origin/<branch-name>
#2.建立本地分支和远程分支的关联
git branch --set-upstream <branch-name> origin/<branch-name>
#3.pull and push
git pull
git push origin <branch-name>

#把git提交变成一条线，操作可以把本地未push的分叉提交历史整理成直线；
git rebase

# idea测试一下
git config --global user.name

#再来一次
once again

#远程来一次
haha

#冲突测试

#测试一下冲突怎么解决
test
