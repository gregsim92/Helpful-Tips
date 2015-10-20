#git cheatsheet

### start a new project 

```shell
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m"initial commit"
```

### Do some work and then save it

First, do some work!

```shell
$ git status
$ git add <whatever file>
$git commit -m"I made some changes, missed a step as well"
```


### Share my work!

create a repo

```shell
$ git remote add origin git@github.com:<username>/<name of repo>.git
$ git push -u origin master
```


### Help someone else with their code

find the code on github that you want to contribute to

then FORK IT

```shell
$ git clone git@github.com:<username>/<repo_name>.git
```

then, make some changes you find important

```shell
$ git add <your files>
$ git commit -m"Thorough explanation of what changes you made since this wasn't your work" 
$ git push origin master
```



