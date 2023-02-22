# GIT AND GITFLOW CHEATSHEET



## GIT 

---

### Basic or common Git Commands


```shell

$ git init # Create a new git repository

$ git add # Add files to the staging area

$ git status # Check the status of the repository

$ git commit -m # Move files from the staging area to the local repository with a commit message

$ git log # View the file versions in the repository

$ git clone # Clone a remote repository

$ git push # Modify the remote repository with your new changes

$ git pull # Update your local repository with the latest changes from the remote

$ git add . # Add all modified files to the staging area
```

---

## GIT FLOW 
---

### To install git flow on Debian Linux, 

You need to have git installed first. Here are the commands you can execute in your terminal as sudo or root:

```

$ sudo apt-get update

$ sudo apt-get install git-flow

```



### INITIALIZE
Once you're inside your git directory or cloned repository, initialize git flow:

```

$ git flow init

```

### GIT FLOW BRANCHES

![](https://www.campingcoder.com/post/20180412-git-flow.png)

* **Master**: Main branch that maintains the stable version of a software.
* **Develop**: Branch used by one or more programmers for a software in testing mode.
* **Feature**: Temporary or local branch, used for each programmer to develop a specific function (library, function, class, etc.).
* **Release**: Temporary branch only for publishing version tags and synchronizing develop with master. This is done when we have a stable version of software or a milestone for delivery.
* **Hotfix**: Temporary branch used to fix critical errors or bugs in production code, usually used in emergency mode.

#### FEATURES


---


**1. START A FEATURE **

```
$ git flow feature start MYFEATURE

```
> Replace "MYFEATURE" with the name you want to give your feature.
---

**2. FINISH A FEATURE**

```


$ git flow feature finish MYFEATURE # Finish development of a feature.

$ GETTING PUBLISHED FEATURES

$ git flow feature pull origin MYFEATURE # Get a feature published by another.

$ git flow feature track MYFEATURE # You can keep track of your changes.

```

#### RELEASE
---

**HOW TO PUBLISH A VERSION**

```
$ git checkout master
 
$ git pull
 
$ git checkout develop
 
$ git pull
 
$ git flow release start 1.0
 
$ git flow release publish 1.0
 
$ git flow release finish 1.0
 
$ git push origin --all --follow-tags

```

---

#### HOTFIX
---

**HOW TO PUBLISH A HOTFIX**

```

$ git checkout develop
 
$ git pull
 
$ git checkout master
 
$ git pull
 
$ git flow hotfix start (Name)
 
# Make changes
 
$ git status # Check the file in red
 
$ git add . # add files
 
$ git commit -m # 'Write a comment'
 
$ git flow hotfix finish (name)
 
# Remember to put a fixed version tag 1.2.x for example 1.2.2
# You were on master, and then you should be on the development branch 

$ git push origin --all --follow-tags
 
```

## LICENSE

```
Copyright (C) 2023 DECENTRALIZED CLIMATE FOUNDATION A.C.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License". 
```

## CONTACT AND DEVELOPERS
> Work developed in collaboration with the [Decentralized Climate Foundation](https://decentralizedclimate.org).

- [Gustavo Bermudez](mailto:nizaries44@gmail.com)

Revisor:

- [David E. Perez Negron R.](mailto:david@neetsec.com) 


## REFERENCES
\[1\]  Daniel Kummer, "Git-flow cheatsheet", https://danielkummer.github.io/git-flow-cheatsheet/index.html), 2023.

\[2\] www.campingcoder.com, "How to use git flow", https://www.campingcoder.com/2018/04/how-to-use-git-flow/, 2023.  
