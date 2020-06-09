#git的新建项目目录

* mkdir 名字_git
   *这个是创建目录
   
* cd 名字_git
   *进入这个目录

* ls -al
	* 查看次目录的内容

* git init
	*初始化git仓库

* git config --global user.name "名字"
git config --global use.email "邮箱"
	*创建一个配置

* git config --global --list
	* 检查配置的结果

* git status
	* 查询状态

* pwd
	*查询目录

* git add
	*添加跟踪文件，也就是说把未跟踪的文件从工作区移到暂存区
	*如果add .   就是在add后面加一点就是移所有文件 

* git re --cached <file>
	* 移除暂存的文件

* git commit 
	* 将暂存区的文件移到git仓库

* git log
	* 查看使用者做过什么操作