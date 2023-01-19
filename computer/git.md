# Git快速上手
## 我自己怎么用Git维护我的项目

git init

git status

edit

git add

git commit

*git remote add origin

*git push --set-upstream origin master

git pull

git push

## 我如何通过Git参与别人的项目

fork

git clone

edit

git push

pull request

## 我如何让别人通过Git参与我的项目

## SSH

```shell
ssh-keygen -t ed25519 -C "your_email@example.com"
```

通过上面的命令在本地生成密钥对儿文件

将.pub文件上传至github

## 命令

| 命令             | 用途                | 频次 |
| ---------------- | ------------------- | ---- |
| git status       | 查看git仓库的状态   |      |
| git add          | 将文件提交给git管理 |      |
| git commit -m    | 游戏存档            |      |
| git branch       | 查看&创建分支       |      |
| git checkout     | 切换分支            |      |
| git branch -d/-D | 删除分支            |      |
| git pull         | 将源拉取到本地      |      |
| git push         | 将本地推送至源      |      |

## 已知问题
**看不到.git**
因为.git默认是隐藏的，所以每个人电脑上关于隐藏文件的查看设置不同，可能会看不到。
解决：
1.搜索关于如何查看隐藏文件，如何在vscode中看到.git文件夹等内容，自行解决；
2.在运行了`git init`的文件夹内执行`git status`，如果有返回结果，表明git初始化成功了。