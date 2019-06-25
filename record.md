管理修改
修改但未add
比较工作区与暂存区（即上次git add的内容）的不同
比较所有修改文件的不同
$ git diff

比较指定修改文件的不同
$ git diff <file-name>

修改已add但未commit
比较暂存区与仓库分支（上次git commit）的不同
$ git diff --staged
或
$ git diff --cached

git dev test