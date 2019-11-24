# git-setting-ubuntu
setting git in ubuntu

1. install git
* $ apt-get install git-core

2. set github account 
* $ git config --global user.name "username"
* $ git config --global user.email "email"

3. set ssh key
* $ ssh-keygen -t rsa -b 4096 -C "email"
* $ eval "$(ssh-agent -s)"
* $ ssh-add ~/.ssh/id_rsa

4. view ssh key
* $ vi ~/.ssh/id_rsa.pub

5. copy ssh key and register it to github setting page

