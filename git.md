试着输入`git`，看看系统有没有安装git

	$ git
	The program 'git' is currently not installed. You can install it by typing:
	sudo apt-get install git

输入以下命令来安装git

	$ sudo apt-get install git

安装完git后，进行个人设置

	$ git config --global user.name "Your Name"
	$ git config --global user.email "email@example.com"
	
git常用命令
	
	git init
	git add
	git commit
	git diff
	git status
	git log
	git reflog

创建ssh公钥
	
	$ ssh-keygen -t rsa -C "youremail@example.com"
	$ git remote add origin git@github.com:michaelliao/learngit.git
	$ git push -u origin master
	
	$ git clone git@github.com:michaelliao/gitskills.git