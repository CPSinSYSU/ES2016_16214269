**第一步:** **github.com** 上添加新仓库 "Create New Repository"

**第二步:** 本地关联远程库.添加后，远程库的名字就是 **origin**，这是 **Git** 默认的叫法，也可以改成别的，但是 **origin** 这个名字一看就知道是远程库。
```sh
git remote add origin https://github.com/Durant35/[Repository Name].git
```
　把本地库的内容推送到远程，用 **git push** 命令，实际上是把当前分支 **master** 推送到远程。
　由于远程库是空的，我们第一次推送 **master** 分支时，加上了 **-u** 参数，**Git** 不但会把本地的 **master** 分支内容推送的远程新的 **master** 分支，还会把本地的 **master** 分支和远程的 **master** 分支关联起来，在以后的推送或者拉取时就可以简化命令。
```sh
git push -u origin master
```
　把本地 **master** 分支的最新修改推送至 **GitHub**！
```sh
git push origin master
```

**第三步：** 查看改变
　查看本地文件夹改变
```sh
git status
```
　查看本地文件改变
```sh
git diff "file name"
```
　查看本地与远程库区别
```sh
git diff master origin
```

**第四步:** 文件/文件夹创建、编写
　　　<font color="green">**git add "file name"**</font>　　　　# 创建
　　　<font color="green">**git rm "file name"	**</font>　　　　 # 删除			
　　　<font color="green">**git add .	**</font>　　　　 　　　 　# git add all files changed

**第五步:** 先本地提交，后远程提交
　　　<font color="green">**git commit -m "messages"**</font>
　　　<font color="green">**git push origin master**</font>

**第六步:** **git** 版本回退
(注意 **hard** 前面是两个**"-"**)
```sh
git reset --hard commit_id
```
　1) **HEAD** 指向的版本就是当前版本
　2) **commit_id** 通过以下命令获取
```sh
git log　　　 # 查看提交历史	--> 回退到过去哪个版本
git reflog　　# 查看命令历史 	--> 回到未来的哪个版本
```
