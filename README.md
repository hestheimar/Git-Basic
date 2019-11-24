# initial setting git in ubuntu

__1. install git__
* $ sudo apt-get install git-core

__2. set github account__ 
* $ git config --global user.name "username"
* $ git config --global user.email "email"

__3. generate ssh key__
* $ ssh-keygen -t rsa -b 4096 -C "email"
* $ eval "$(ssh-agent -s)"
* $ ssh-add ~/.ssh/id_rsa

__4. view ssh key__
* $ vi ~/.ssh/id_rsa.pub

__5. copy ssh key and register it to github setting page__
