+++
title = "Git Reference"
author = ["Max"]
draft = false
+++

\#dev/basic


## NOTES {#notes}


### 1.6 起步 - 初次运行 Git 前的配置 {#1-dot-6-起步-初次运行-git-前的配置}

\`\`\`sh


## 设置用户信息 {#设置用户信息}

$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com


## 文本编辑器 {#文本编辑器}

$ git config --global core.editor emacs


## 检查配置信息 {#检查配置信息}

$ git config --list
\`\`\`


### 1.7 起步 - 获取帮助 {#1-dot-7-起步-获取帮助}


### 初始化项目 {#初始化项目}

\`\`\`sh


## 创建新仓库 {#创建新仓库}

$ git clone git@gitlab.com:maxoxo-learning/git/init.git
$ cd init
$ touch README.md
$ git add README.md
$ git commit -m "add README"
$ git push -u origin master


## 在现有目录中初始化仓库 {#在现有目录中初始化仓库}

$ cd existing\_folder
$ git init
$ git remote add origin git@gitlab.com:maxoxo-learning/git/init.git
$ git add .
$ git commit -m 'initial commit'
$ git push -u origin master


## 添加到现有仓库中 {#添加到现有仓库中}

$ cd existing\_repo
$ git remote rename origin old-origin
$ git remote add origin git@gitlab.com:maxoxo-learning/git/init.git
$ git push -u origin --all
$ git push -u origin --tags
\`\`\`


### 提交 {#提交}

\`\`\`sh


## 添加遗忘的文件，最终你只会有一个提交 - 第二次提交将代替第一次提交的结果。 {#添加遗忘的文件-最终你只会有一个提交-第二次提交将代替第一次提交的结果}

$ git commit -m 'initial commit'
$ git add forgotten\_file
$ git commit --amend


## 撤消对文件的修改 {#撤消对文件的修改}

$ git checkout -- CONTRIBUTING.md
\`\`\`


### 远程仓库 {#远程仓库}

\`\`\`sh


## 查看远程仓库 {#查看远程仓库}

$ git clone <https://github.com/schacon/ticgit>
$ cd ticgit
$ git remote


## 添加远程仓库 {#添加远程仓库}

$ git remote add <shortname> <url>
$ git remote add pb <https://github.com/paulboone/ticgit>
$ git fetch pb		# 使用 short name 来取代完整的 url


## 从远程仓库中抓取与拉取 {#从远程仓库中抓取与拉取}

$ git fetch [remote-name]


## 推送到远程仓库 {#推送到远程仓库}

$ git push origin master


## 查看远程仓库 {#查看远程仓库}

$ git remote show origin


## 远程仓库的移除 {#远程仓库的移除}

$ git remote rm paul


## 远程仓库的重命名 {#远程仓库的重命名}

$ git remote rename pb paul
\`\`\`


### 标签 {#标签}

\`\`\`sh


## 列出所有标签 {#列出所有标签}

git tag


## 列出特定标签 {#列出特定标签}

git tag -l '1.8.\*'


## 创建附注标签 {#创建附注标签}

git tag -a v1.4 -m 'my version 1.4'


## 查看标签对应的提交信息 {#查看标签对应的提交信息}

git show v1.4


## 创建轻量标签，只保存标签，不带有其他信息 {#创建轻量标签-只保存标签-不带有其他信息}

git tag v1.4-lw


## 后期打标签，为已经提交的内容打标签 {#后期打标签-为已经提交的内容打标签}

git tag -a v1.2 9fceb02


## 将标签放入远程仓库 {#将标签放入远程仓库}

git push origin v1.5


## 推送多个标签 {#推送多个标签}

git push origin --tags


## 检出标签 {#检出标签}

git checkout -b version2 v2.0.0


## 为发布打标签 {#为发布打标签}

git tag -s v1.5 -m 'my signed 1.5 tag'
\`\`\`


### 远程分支 {#远程分支}

\`\`\`sh


## 跟踪远程分支，相当于建立一个与远程分支相关的本地分支 {#跟踪远程分支-相当于建立一个与远程分支相关的本地分支}

git checkout --track remotes/origin/branch-name


## 跟踪远程分支，并在本地建立相关分支 {#跟踪远程分支-并在本地建立相关分支}

git checkout -b local-branch --track remotes/origin/remotes-branch


## 删除远程分支中，某个与 tag 名称相同的分支 {#删除远程分支中-某个与-tag-名称相同的分支}

git push origin :refs/heads/branch-name
or
git push origin --delete serverfix


## 删除远程分支中，某个与 branch 名称相同的tag {#删除远程分支中-某个与-branch-名称相同的tag}

git push origin :refs/tags/branch-name


## 查看 remote 地址、远程分支 {#查看-remote-地址-远程分支}

git remote show origin


## 清除已经不存在的远程分支 {#清除已经不存在的远程分支}

git remote prune origin
\`\`\`


### 本地分枝 {#本地分枝}

\`\`\`sh


## 暂存当前的修改 {#暂存当前的修改}

git stash


## 获取暂存清单 {#获取暂存清单}

git stash list


## 应用暂存内容 {#应用暂存内容}

git stash apply
\`\`\`


### 10.7 Git 内部原理 - 维护与数据恢复 {#10-dot-7-git-内部原理-维护与数据恢复}

\`\`\`bash


## 查看仓库当前的位置 {#查看仓库当前的位置}

git log --pretty=oneline [branch name (option)]


## 重置仓库位置 {#重置仓库位置}

git reset --hard [SHA-1]


## 查看操作记录 {#查看操作记录}

git reflog


## 查看操作详情 {#查看操作详情}

git log -g


## 创建新的分支来储存恢复 {#创建新的分支来储存恢复}

git branch recover-branch [SHA-1]


## 移除操作记录 {#移除操作记录}

rm -Rf .git/logs/


## 移除记录后需要重建记录 {#移除记录后需要重建记录}

git fsck --full
\`\`\`


## REFERENCE {#reference}


## [Git - Book](<https://git-scm.com/book/zh/v2>) {#git-book--https-git-scm-dot-com-book-zh-v2}
