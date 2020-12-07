# Git Aliases

### git com; Checkout master/main, pull origin master/main and print status
#### master
`git config --global alias.com "! git checkout master && git pull origin master && git status"`
#### main
`git config --global alias.com "! git checkout master && git pull origin master && git status"`

---

### Show all you alias commands
git alias

`git config --global alias.alias "config --get-regexp ^alias\."`

---

### Shorthand for git status
git s;

`git config --global alias.s "status"`

---

### Add all files and commit
git c

`git config --global alias.c "! git add -A && git commit -m \"work in progress\" && git status"`

---

### Create a branch
git b "branchName"

`git config --global alias.b "! git checkout -b $1"`

---
