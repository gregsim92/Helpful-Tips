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
finish what you started working on, then push any additional commits

File a Pull request with the commits in it that you want to share. Make sure that you include a good explanation in the pull requet of what this is , what its intended to do, add some nice language, rather than insulting their mistakes.



### Creating shortcuts using aliases

```shell
$ git config --global alias.<new command> <original command>

Git Aliases are a way to limit the number of keys necessary to execute a command. By creating an alias for an existing command, you make it easier for the computer to make sense of what you wish to execute.




# Helpful-Tips
