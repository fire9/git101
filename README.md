Git 101 Guide
=============

create a new repository

```bash
$ git init git101
$ cd git101
$ echo "Hello Git" >> README.md
$ git add README.md
$ git commit -m "initial repo"
```

push git101 to remote repository

> create git101 repository in your github account

```bash
$ git remote add origin git@github.com:fire9/git101.git
$ git push -u origin master
```
