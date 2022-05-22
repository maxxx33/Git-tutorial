###### SSH Connections and keys
**Generate new key**
ssh-keygen -t rsa -b 4096 -C "email@email.com" 

**List keys**
ls | grep keyname

**View public key**
cat keyname.pub

**Initiate SSH agent connection**
eval "$(ssh-agent -s)"

**Add private key to SSH connection**
ssh-add keyname

###### GIT Codes

**Initialize Git repo created locally**
git init

**Untraced files**
git status

**Add and track files**
git add .

**Commit to changes**
git commit -m "message" -m "message2"

**Push modifications online to Github**
git push -u origin master
git push 

**Add new repository created locally**
git remote add origin repository_address.git

**Show remote repositories**
git remote -v

**Clone repository**
git clone repository_address.git

