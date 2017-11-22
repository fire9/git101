Git 101 Guide
=============

#### create a new repository

```bash
$ git init git101
$ cd git101
$ echo "Hello Git" >> README.md
$ git add README.md
$ git commit -m "initial repo"
```

#### push git101 to remote repository

> create git101 repository in your github account

```bash
$ git remote add origin git@github.com:fire9/git101.git
$ git push -u origin master
```

#### import git flow

```bash
➜  git101 (master) ✔ git flow init -d
Using default branch names.

Which branch should be used for bringing forth production releases?
   - master
Branch name for production releases: [master]
Branch name for "next release" development: [develop]

How to name your supporting branch prefixes?
Feature branches? [feature/]
Bugfix branches? [bugfix/]
Release branches? [release/]
Hotfix branches? [hotfix/]
Support branches? [support/]
Version tag prefix? []
Hooks and filters directory? [/Users/fire9/git101/.git/hooks]
```
