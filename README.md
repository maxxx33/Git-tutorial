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

**Push modifications online to Github:**
```
git push -u origin master
git push 
```

## Branches

**List all branches available**
```git branch```

**Create new branch -b:**
```git checkout -b feature-readme```

**Switch between branches - tab feature**
```git checkout branch_name```


