# Git Cheatsheet

### Start a new project

```shell
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "initial commit"
```

### do some work and then save it

First, do some work!

```shell
$ git status
$ git add <whatever file> 
$ git status
$ git commit -m "I made a bunch of changes"
```

### share my work with the world!

First, create a repo via github

```shell
$ git remote add origin git@github.com:<githubusername>/<repositoryname>.git
$ git push -u origin master
```