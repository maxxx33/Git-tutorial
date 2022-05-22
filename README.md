## SSH Connections and keys
**Generate new key:**
```ssh-keygen -t rsa -b 4096 -C "email@email.com" ```

**List keys:**
```ls | grep keyname```

**View public key:**
```cat keyname.pub```

**Initiate SSH agent connection:**
```eval "$(ssh-agent -s)"```

**Add private key to SSH connection:**
```ssh-add keyname```

**List files and folders:**
```ls -la```

## Repository

**Initialize Git repo created locally:**
```git init```

**Add new repository created locally:**
```git remote add origin repository_address.git```

**Show remote repositories:**
```git remote -v```

**Clone repository to local machine:**
```git clone repository_address.git```

## Updates changes to code

**Untraced files:**
```git status```

**Add and track files:**
```git add .```

**Commit changes made locally:**
```git commit -m "message" -m "message2"```

**Commit and add for existing files:**
```git commit -am "message"```

**Push modifications online to Github:**
```
git push -u origin master
git push 
```

## Branches

**List all branches available:**
```git branch```

**Create new branch -b:**
```git checkout -b feature-readme```

**Switch between branches - tab feature:**
```git checkout branch_name```

**Change branch name to main locally:**
```git branch -m main```

**Compare changes in 2 branches:**
```git diff branch_name```

**Update branch from Github to local:**
```git pull origin branch_name```

**Delete branch local machine:**
```git branch -d feature-readme```

**Merge branches locally**
```git merge branch_name(main)```

## Undoing changes made to code
**Undoing add**
```git reset file_name```

**Undoing merging - HEAD is a pointer**
```git reset HEAD~1```

**Log of all commits**
```
git log
git reset hash
```

**Undoing all changes**
```git reset --hard hash```