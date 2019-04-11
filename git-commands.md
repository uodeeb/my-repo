A step by step guide 
ADD A PROJECT TO GITHUB
A] create your GitHub repo
1- GO TO >> www.github.com
2- open an account
3- At the top right >>> press new repository
4- Name your repository
5- create your repository
B] on your git bash command line
6- USING YOU GIT BASH >>>go to your project director
	USER MINGW64 /[YOUR-WORK-DIR]
	$
7- to start tracking your folder with git>>>Type in the command line >>>>
	$ git init 
8- to add your folder to your github repo >>>Type in the command line >>>>
	$ git remote add origin <your-repo-url>
9- to check your remote repo >>>Type in the command line >>>>
	$ git remote -v
		You can see >>>
	https://github.com/<user-name>/<repo-name>.git(fetch)
	https://github.com/<user-name>/<repo-name>.git(push)
10-to add all your folder files to be tracked >>> Type in the command line >>>>
	$ git add .
11- to commit all changes >>> Type in the command line >>>>
	$ git commit -m “<name your commit to easily track>”
12- to push your files to the remote repo >>> Type in the command line >>>>
	$ git push origin master
C] on your GitHub repo
13- refresh the repo page >>> now all your project files at your remote repo
