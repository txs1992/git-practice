# git-practice

### git 基本操作

git add 添加文件

git mv 修改文件名

git rm 删除文件

git commit 提交历史

### git 分支操作

git checkout branchName 切换分支

git checkout -b branchName 创建新分支并切换到该分支

git branch / git branch -v 查看分支

git branch newBranchName commit/branchName 创建新分支，基于 commit 或者分支名

git branch -D branchName 删除分支

### 查看版本演变历史

git log 查看历史

git log --oneline 只看 commit 提交信息

git log -n2 查看最近两条提交历史

git log --graph 图形化查看历史

git log --all 查看所有分支提交历史

### 查看 git objects 文件

git cat-file -t xxx 查看文件类型

git cat-file -p xxx 查看文件内容
