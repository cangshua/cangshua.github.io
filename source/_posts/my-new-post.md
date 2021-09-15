---
title: my new post
date: 2021-08-23 08:49:53
tags:
---

1.在github创建一个仓库 名字：github用户名.github.io

2.找到博客代码的目录

3.生成静态资源文件

```
hexo g
```

4.将public目录复制到一个新的文件夹里面



5.初始化git并且关联

```
git init
git add.
git commit -m '描述'
git remote add origin 远程地址
git push origin master
```

6.预览：github用户名.github.io

# 怎么使用git

```node
git clone 地址：克隆一个仓库地址
git init:git 初始化 生成.git文件
git add 文件名字 ：git add .：将所有的文件提交到缓存，没有提交记录
git commit -m '描述信息'：提交到本地
git log ：提交日志
git status ：查看git状态
git remote add origin 地址：关联远程地址
git remote -v ：查看有没有关联远程地址
git push origin 分支：推送到远程
git pull：从远程拉取
git pull origin 分支名字
#团队协作：分支
命令：以姓名命名
默认分支（主分支）master
合并：dev分支
git branch A
git branch B

git checkout A
```

