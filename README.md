# GIT система управления версиями (CVS)
Работа через консоль Linux или git-bash для windows
***
## Создать проект
1) Создать на сайте репозиторий
2) через консоль, на ПК, копируем данные 'git clone https://github.com/...'
3) сконфигурировать git:
'git config user.name "user"'
'git config user.email user@mail.ru'
4) получили рабочую независимую версию на своем ПК
***
Для просмотра истории 'git log'
Для просмотра изменений 'git diff'
***
Текущий статус репозитория 'git status'
Если есть изменения, то 'git add file.name'
Закоммитить изменений 'git commit -m "message"'
отправить (запушить) в оригинальный реп 'git push'
Для того, чтобы забрать изменения с оригинального репа 'git pull
Чтобы добавить в предыдущий коммит 'git commit --amend'
***
Проверить текущий статус 'git status'
Посмотреть изменения 'git diff'
Если есть изменения, то
'git stash'
'git pull'
'git stash pop'
'git add filename'
'git commit -m ""'
'git push'
