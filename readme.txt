Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.

git remote add origin git@github.com:michaelliao/learngit.git
learngit：github上的远程仓库名
michaelliao：github上的账户名
git push -u origin master
把本地master分支的最新修改推送至GitHub，现在就拥有了真正的分布式
版本库！
由于远程库是空的，我们第一次推送master分支时，加上了-u参数，Git>不但会把本地的master分支内容推送的远程新的master分支，还会把本地
的master分支和远程的master分支关联起来，在以后的推送或者拉取时就
可以简化命令。git push origin master
