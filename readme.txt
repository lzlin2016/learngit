Git is a distributed version control system.
Git is a free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.


$ git checkout master 切换分支
$ git checkout -b feature1 创建并切换到新分支
$ git branch -d feature1 峰值
$ git merge --no-ff -m "merge with no-ff" dev 合并分支, 禁用fast forward


小结

Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

感觉本站内容不错，读后有收
 
