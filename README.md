# Git-Aliases

* git config --global alias.com "! git checkout master && git pull origin master && git status"
* git config --global alias.alias "config --get-regexp ^alias\."
* git config --global alias.s "status"
* git config --global alias.c "! git add -A && git commit -m \"work in progress\" && git status"
* git config --global alias.b "! git checkout -b $1"
