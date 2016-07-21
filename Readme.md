# Projet git-tutorial

```
git init
git config --global user.email "votreemail@wtf.com"
git config --global user.name "Nicolas Giard"
git status
git add Readme.md
git commit -m "Initialisation du projet"
git log
git remote add github https://github.com/poec-bg/git-tutorial.git
git push -u github master
```

```
git clone -o github https://github.com/poec-bg/git-tutorial.git

```

```
touch prenom.html
git add prenom.html
git push master
```
```
git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative
```


```
git remote -v
git branch -r
```