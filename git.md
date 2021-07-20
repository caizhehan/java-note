# git的基本使用

## git的代码提交步骤
1. git add .: git add是将代码存在暂存区
2. git commit -m "xxx": git commit 是提交代码到本地仓库
3. git push: git push是提交到远程仓库中

## git同步代码步骤
1. git stash: 在代码更新之前，先用git stash存储起来
2. git pull: 同步远程仓库代码并合并到主线上
3. git stash pop: 把暂存的代码pop出来

## git 分支的使用

git checkout -b xxx: 新建分支并切换到该分支
git switch xxx: 切换分支
git checkout -d xxx: 删除分支

## git tag的使用

git tag xxx: 新建tag
git tag -d xxx: 删除本地tag
git push origin :refs/tags/xxx: 删除远程分支
hello world!!!
life is shit!!
