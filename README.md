https://www.youtube.com/watch?v=SWYqp7iY_Tc


-	Install Git from 
	https://git-scm.com/download/win

-	Check Git Version command
	git --version
	
-	Create Folder and Right click open with (Git Bash Here)

-	Create html file Command
	touch filename.html

-	Initialize Git Command (it will create one repository in your folder and folder is hiddden)
	git init

-	Set global Configuration of Git (Example Name, Email)
	git config --global user.name 'nimesh'
	git config --global user.email 'nimesh.prajapati@hexpress.net'

-	To add File in Master repository Command (check in Repository file)
	git add filename.html

-	To know status of all files Command
	git status

-	To upload cached version of file
	git rm --cached filename.html

-	Add multiple file with same extention
	git add *.html
	git status
	
-	Add all files
	git add .
	git status

-	To Commit all File
	git commit
	(It will open one editor and add comment and close the editor)
	
-	Clear Commands
	clear

-	Commit after the file changes
	git commit -m
	
-	Create gitignore file for ingore file which you want
	touch .gitignore
	
-	For example if you want to ignore log.txt file then follow below steps
	-	Add File name in .gitignore file
	-	check status (git status)

-	Create Branch
	git branch branch_name
	
-	To switch one branch to another
	git checkout branch_name
	(When you want to switch you have to commit all changes of exist branch)

-	To Merge One branch to another
	git merge branch_name
