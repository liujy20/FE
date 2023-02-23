Git is a distributed version control system.
Git is free software distributed under the GPL.

---

### git命令

git init//创建版本库

rm -rf .git//删除版本库

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

git rm test.txt
git commit -m "remove test.txt"//版本库删除文件

---
### 远程仓库

git remote add origin git@github.com:michaelliao/learngit.git//关联远程仓库取名为origin

git push -u origin master//第一次推送关联master

git push origin master//后续推送

git remote -v//查看远程库

git remote rm origin//删除远程库，实际为解绑远程库

git clone git@github.com:michaelliao/gitskills.git//克隆远程库

---

### 分支管理

- git switch -c dev//创建并切换分支
- git branch dev//创建分支
  git switch dev//切换分支

git branch//查看分支

git switch master
git merge dev//合并dev分支到master分支

git branch -d dev//删除分支

git log --graph//查看分支合并图





