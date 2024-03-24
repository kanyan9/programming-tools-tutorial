# Git
## 版本控制发展

## Git介绍
Git是一个分布式的版本控制系统。
## Git原理
### Git架构


Git架构的几个核心概念包括：本地工作区（Working Directory）、暂存区（Staging Area）、版本库（Repository）和远程仓库（Remote Repository），分别具备以下功能。
- 本地工作区：这是在本地机器上存储代码文件的地方，也是开发人员直接编辑和修改代码的地方。
- 暂存区： 在本地工作区中修改代码后，可以使用git add命令将这些修改添加到暂存区，准备提交到版本库。
- 版本库： 版本库包含着完整的项目历史记录，每次提交到暂存区的改动都会被永久存储在版本库中。
- 远程仓库： 远程仓库是位于远程服务器上的版本库副本，用于团队成员之间的代码共享和协作。


### Git工作流程

## Git安装
在linux上可以通过发行版自带的包管理工具安装git，如果你使用的是Fedora，你可以使用dnf：
```
sudo dnf install git
```
如果你使用的是基于Debian的发行版，如Ubuntu，你可以使用apt：
```
sudo apt install git
```

## Git使用前最小准备
安装完成Git之后，还要完成一些配置才可以更好的使用Git，其中最公用的是配置Git使用者的用户名和邮箱信息，我们也把配置用户名和邮箱信息成为使用Git前的最小准备，配置用户名和邮箱信息主要通过以下命令：
```
$ git config [--local|--global|--system] user.name "your name"
$ git config [--local|--global|--system] user.email "your email"
```
在设置时会用到--local、--global和--system参数来规定设置的有效范围，--local表示对本仓库有效，--global参数表示对当前用户的所有仓库有效，--system表示对本系统的所有用户有效。一般情况下选择--global参数完成用户名和邮箱信息设置。

## Git常用命令

## 扩展阅读
Git官网：https://git-scm.com/