If you use openssh on git then you need to check your ssh refer to this link: https://help.github.com/en/articles/connecting-to-github-with-ssh

Local:

1. git init
2. add .gitignore
3. git status
4. git add --all (git add .)
5. git status
6. git commit -m "adds .gitignore file"
7. git status
8. git log


Master/Origin:

ceate repository
1. git remote add origin git@github.com:dannyadil/gittest.git
2. git push -u origin master


Collaborate on github: 

1. Fork (do it from github)
	-> Fork gitinfo from dannyadil to dannysibarani
2. Clone (on git bash)
	i. cd gitinfo
	ii. git remote add upstream git@github.com:dannyadil/gitinfo.git
	iii. This will now allow you to pull in changes from the source locally and merge them, like so:
		a. git fetch upstream
		b. git merge upstream/master
3. 
	