# Git Aliases

### git com; Checkout master/main, pull origin master/main and print status
#### main
`git config --global alias.com "! git checkout main && git pull origin main && git status"`

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

### Log oneline decorate all graph

`git config --global alias.lg "log --oneline --decorate --all --graph"`

---
