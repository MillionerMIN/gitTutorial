#Git Tutorial

##Install git for brew
Install homebrew in Mac
[Homebrew](https://brew.sh/ "Homebrew")
Install to use 

```
brew install git
```
----
##Setting for global configuration
```
git config --global user.name
git config --global user.email
```
###For initialization git in project to use command:
```
git init
```
###GIT COMMAND:

1. git status    проверка статуса файлов
2. git add .  add all files
3. git commit -m ‘text commit’  добавит описанте комита
4. git checkout -b <name> <base>   создание ветки пример (git checkout -b portal.lilloo/styleUI  origin/master)
5. git merge <name ветки с которой соеденить>
6. git checkout master становишся на ветку мастер
7. **git push --delete origin hotfix. удалить ветку удаленно**
8. cat .git/config  команда для изменения файла конфигурации
9. git branch -a покажет локальные и удаленные ветки
10. git diff  позволяет посмотреть изменения
11. git fetch  забирает удаленные изменения
12. git pull забирает удаленные изменения и мержит в текущий branch
13. git merge —abort  отменяет все изменения решения конфликтов и откатывает назад
14. git mergetool    запускает vscode для решения конфликтоав