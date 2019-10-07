我是分支 DEV
git init 初始化仓库
git clone 克隆/赋值
git add . 添加到暂存区
git commit -m '描述' 描述
git status 查看当前分支状态
git remote add origin url 关联远程仓库
git remote 查看远程仓库的信息
git remote rm origin 清除origin链接
git push origin master push到origin的分支 master
git branch 查看本地分支
git branch --all 查看本地及远程所有分支    * 当前选中的分支
git pull origin master 下拉信息(即下载)
当本地和远程仓库同时被修改时，会出现冲突。解决冲突:要的留,不要的删
git chackout -b dev 新建本地 dev 并切换到本地 dev 分支
我们都是web精英