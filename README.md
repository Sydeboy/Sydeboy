# git-study

git init # 初始化

git add README.md  # 新建仓库需要

git add .  # 添加所有文件

git commit -m "first commit"

git branch -M main  # 将分支变成main，取代传统的master
## 本地仓库与远程github关联
git remote add origin https://github.com/Sydeboy/git-study.git 
## 远程有readme.md，先拉一下
git pull --rebase origin main

git push -u origin main # 第一次提交需要u

## 将代码上传github的默认分支
git --version
git config --global init.defaultBranch main

git reset . # 取消git add .操作

git pull # 远程拉取到本地
