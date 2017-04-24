# -
一些杂项的命令

------------------------------------------git
1.
#在当前目录新建一个Git仓库
git init

2.
#下载一个项目和它的整个代码历史
#url格式:https://github.com/[username]/reposName
git clone [url]

3.
#添加文件到暂存区
git add [file1] [file2]

4.
#删除工作区文件,并且将这次删除放入暂存区
git rm [file1]  [file2]

5.
#改名文件,并且将这次改名放入暂存区
git mv [file-origin] [file-rename]

6.
#提交暂存区到仓库 ,[message]:本次变动的概述
git commit -m [message]

7.
#直接从工作区提交到仓库
#前提该文件已经有仓库中的历史版本
git commit -a -m [message]

8.
#显示更变信息
------------------------------------------
