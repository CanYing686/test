# Git 使用方法

本文档提供了常用 Git 命令的简单概述，这可以帮助您更高效地管理和追踪您的代码更改。

## 创建本地仓库

使用 `git init` 在本地创建一个新的 Git 仓库：

```bash
git init
```

## 追踪文件和提交更改

将文件添加在 Git 暂存区

```bash
git add <文件路径>
```

将暂存区的文件提交到仓库

```bash
git commit -m "你的提交信息"
```

## 查看分支信息

```bash
git branch
```

## 查看仓库状态

查看仓库的当前状态，如哪些文件被修改或暂存

```bash
git status
```

## 查看提交历史

```bash
git log --all
```

## 回退版本

> 注意，这将会丢弃当前版本后的所有版本

```bash
git reset --hard <COMMIT_ID>
```

## 添加远程仓库和查看远程仓库

添加一个远程仓库叫 origin

```bash
git remote add origin <URL>
```

查看远程仓库

```bash
git remote
```

## 推送到远程仓库

```bash
git push origin master
```

## 查看分支

你可以查看仓库的分支信息:

```bash
git branch
```

## 创建分支

创建一个新的分支:

```bash
git branch <分支名>
```

## 切换分支

切换到一个指定的分支:

```bash
git checkout <分支名>
```

## 合并分支

> 注: 将指定分支的内容合并到当前分支:
```bash
git merge <分支名>
```
