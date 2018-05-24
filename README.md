-	Install Git from [Download Git](https://git-scm.com/download/win).

-	Check Git Version command
	```
	git --version
	```
-	Create Folder and Right click open with (Git Bash Here)

-	Create html file Command
	```
	touch filename.html
	```

-	Initialize Git Command (it will create one repository in your folder and folder is hiddden)
	```
	git init
	```

-	Set global Configuration of Git (Example Name, Email)
	```
	git config --global user.name 'nimesh'
	git config --global user.email 'nimesh.prajapati@hexpress.net'
	```

-	To add File in Master repository Command (check in Repository file)
	```
	git add filename.html
	```

-	To know status of all files Command
	```
	git status
	```

-	To upload cached version of file
	```
	git rm --cached filename.html
	```

-	Add multiple file with same extention
	```
	git add *.html
	git status
	```
	
-	Add all files
	```
	git add .
	git status
	```

-	To Commit all File
	```
	git commit
	```
	-	**(It will open one editor and add comment and close the editor)**
	
-	Clear Commands
	```
	clear
	```

-	Commit after the file changes
	```
	git commit -m
	```
	
-	Create gitignore file for ingore file which you want
	```
	touch .gitignore
	```
	
-	For example if you want to ignore log.txt file then follow below steps
	-	Add File name in .gitignore file
	-	check status (git status)

-	Create Branch
	```
	git branch branch_name
	```
	
-	To switch one branch to another
	```
	git checkout branch_name
	```
	-	**(When you want to switch you have to commit all changes of exist branch)**

-	To Merge One branch to another
	```
	git merge branch_name
	```


==================================

How to Add your Project in Github

==================================

-	Create account in Github
-	Start Project
-	Create new repository (add and select which you need such as)
	-	Repository Name
	-	Desc
	-	Public / Private
-	Follow the command which is show on Github page after create repository

-	Connect to your local project to github remotely command
	```
	git remote
	```
	-	**(Copy remote command path from github) for Example:**
	-	**git remote add origin https://github.com/Nimesh1491/Sampleapp.git**
	
-	Again run remote command
	```
	git remote
	```
	
-	Push Origin file to master file
	```
	git push -u origin master
	```
	-	**(login in Github from Popup)**

**Now You can see your all local files in your github repository file**

**Note :  If you want to add new file in Github repository then follow below steps**
```
git pull
git push
```

**And if you want to add new file in local repository then follow below steps**
```
touch filename
git add .
git commit -m 'commit message'
git push
```

**You can check all the steps on below url [youtube](https://www.youtube.com/watch?v=SWYqp7iY_Tc).**