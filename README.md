# git
git多人开发规范化，版本开发master，dev，dev-0.0.1

# first
git clone 项目地址  下载远程仓库地址
git init    创建.git本地仓库
git add -A 提交 first 的文字修改
git st 查看stage（舞台）
git commit -m 'first' 提交到仓库中
git push 提交到远程仓库

# second
git branch   查看分支（ps: 只有master主分支）
git branch dev  创建dev 分支 
git checkout dev 切换到dev分支（checkout的分支名又叫co）
git add -A 提交 two 的文字修改
git st 查看stage（舞台）
git commit -m 'first' 提交到仓库中
git push 提交到远程仓库

# second 0.1
第二步推上去时出现

![](./_image/2018-06-27-17-39-09.jpg)

远程没有dev分支，
git push --set-uostream origin dev 
远程创建dev分支

![](./_image/2018-06-27-17-40-27.jpg)
重复第二步的步骤再提交一次

# second 0.2 补充下一步计划
git branch -a   查看本地和远程所有的分支，带*号表示当前工作目录的分支

![](./_image/2018-06-27-17-47-11.jpg)

下一步去另一台电脑上下载和创建github账号，下载，
主要目的是想试一试多人办公如何操作


