这是gitee

1、gitee新建仓库，初始化、设置模板、设置分支。例如：tyxian-test
2、gitee：选择tyxian-test代码库，选择要克隆到本地的分支；选SSH。例如：git@gitee.com:tyxian/tyxian-test.git
3、本地新建project文件夹，右键，选择Git Bash Here
4、克隆远程库到本地，例如：git clone git@gitee.com:tyxian/tyxian-test.git
5、将文件添加到本地暂存区：git add .
6、将暂存区内容添加到本地仓库：git commit -m ‘这里随便写’
7、将本地的分支版本上传到远程并合并：git push




报错信息：
1、fatal: not a git repository (or any of the parent directories): .git
在使用Git命令的时候，提示当前没有.git这层目录，所以Git命令设置无效
2、Updates were rejected because the remote contains work that you do更新被拒绝，因为远程包含您所做的工作
因为在本地新建库后，与远程仓库的内容不一致导致的。所以，在向远程库推送的时候，要先进行pull同步远程仓库，让本地新建的库和远程库进行同步