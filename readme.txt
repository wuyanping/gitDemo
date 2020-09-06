git init
git add <文件名>
git commit -m "message"
git status
git diff

版本之间的穿梭 git reset --hard HEAD^
git reset --hard commitId
git log --pretty=oneline
git reflog


工作区-》stage暂存区-》版本库


撤销工作区内容 git checkout -- <file>
分2中情况：
工作修改还没放到stage区，撤销到工作区
工作区已经放到stage区，撤销到stage区


reset 竟可以回退版本，也可以把暂存区回退到工作区

git reset HEAD <FILE>
