Git is a distributed version control system.
Git is free software distributed under the GPL.


git init//创建版本库

git add readme.txt//添加文件

git commit -m ""//提交

git status//仓库状态

git log//日志

git reset --hard HEAD^//版本回退1次

git reset --hard HEAD~100//版本回退100次

git reset --hard 1094a//选择版本

git diff readme.txt//查看文件修改

git diff HEAD -- readme.txt//查看文件工作区和版本区区别

git checkout -- readme.txt
//放入暂存区回到暂存区状态
//未放入回到版本库状态

git reset HEAD readme.txt//暂存区的修改回退到工作区

git rm test.txt//版本库删除文件