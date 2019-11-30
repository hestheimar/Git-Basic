# Git Basic (_on working_)
## Initial Setting (ubuntu, mac)
#### __1. install git__
* sudo apt-get install git-core

#### __2. set github account__
* git config --global user.name "_username_"
* git config --global user.email "_email_"

#### __3. generate ssh key__
* ssh-keygen -t rsa -b 4096 -C "_email_"
* eval "$(ssh-agent -s)"
* ssh-add ~/.ssh/id_rsa

#### __4. view ssh key__
* vi ~/.ssh/id_rsa.pub

#### __5. copy ssh key and register it to github setting page__

## Basic Usage
_after making a repository on github.com_<br>
#### __1. create a new repository on the command line__<br>
* git init
* git add *
* git commit -m "first commit"
* git remote add origin git@github.com:_username_/_repositoryname.git_
* git push -u origin master

#### __2. push an existing repository from the command line__
* git remote add origin git@github.com:_username_/_repositoryname.git_
* git push -u origin master
