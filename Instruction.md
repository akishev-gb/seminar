![Git!](1.jpg)

# Инструкция по работе с Git

## Начальные настройки и установки

*git config --global user.name «Ваше имя английскими буквами» например: Konstantin*

*git config --global user.email ваша почта@example.com*

*git init* – **инициализация локального репозитория**

*git status* – **получить информацию от git о его текущем состоянии**

*git add* – **добавить файл или файлы к следующему коммиту**

*git commit -m “message”* – **создание коммита**

*git log* – **вывод на экран истории всех коммитов с их хеш-кодами**

*git checkout* – **переход от одного коммита к другому**

*git checkout master* – **вернуться к актуальному состоянию и продолжить работу**

*git diff* – **увидеть разницу между текущим файлом и закоммиченным файлом**

## Работа с ветками

*git branch* – **посмотреть список веток в репозитории**

*git branch <название ветки>* – **создать новую ветку**

*git checkout <название ветки>* – **переход к другой ветке**

*git branch -d <название ветки>* – **удалить ветку**

## Работа с удалёнными репозиториями

*git clone <ссылка>* - **клонировать репозиторий из удалённого источника**

*git push* - **отправить изменения в удалённый репозиторий**

*git pull* - **подгрузить изменения из удалённого репозитория**

*git remote add origin <ссылка>* - **привязка локального репозитория к удалённому репозиторию**


# 30 основных команд, которые сделают из вас мастера Git


**Как задать имя пользователя и адрес электронной почты**

*git config --global user.name "Tara Routray"*

*git config --global user.email "dev@tararoutray.com"*

**Кэширование учётных данных**

*git config --global credential.helper cache*

**Инициализация репозитория**

*git init*

**Добавление отдельных файлов или всех файлов в область подготовленных файлов**

*git add somefile.js*

*git add .*

**Проверка статуса репозитория**

*git status*

**Внесение изменений однострочным сообщением или через редактор**

*git commit -m "Your short summary about the commit"*

*git commit*

**Просмотр истории коммитов с изменениями**

*git log -p*

**Просмотр заданного коммита**

*git show 1af17e73721dbe0c40011b82ed4bb1a7dbe3ce29*

*git show 1af17e*

**Просмотр изменений до коммита**

*git diff*

*git diff --staged*

*git diff somefile.js*

**Удаление отслеживаемых файлов из текущего рабочего дерева**

*git rm dirname/somefile.js*

*git rm dirname/*.html*

**Переименование файлов**

*git mv dir1/somefile.js dir2*

**Отмена подготовленных и неподготовленных изменений**

*git checkout somefile.js*

*git reset HEAD somefile.js*

*git reset HEAD*

**Изменение последнего коммита**

*git commit --amend -m "Updated message for the previous commit"*

*git add dir1*

*git commit*

*Here you forgot to add dir2 to commit, you can execute the following command to amend the other files and folders*

*git add dir2*

*git commit --amend --no-edit*

**Откат последнего коммита**

*git revert HEAD*

**Откат заданного коммита**

*git revert 1af17e*

**Создание новой ветки и переход в неё**

*git branch new_branch_name*

*git checkout -b new_branch_name*

**Просмотр списка веток**

*git branch*

*git branch -a*

**Удаление ветки**

*git branch -d existing_branch_name*

*git branch -D existing_branch_name*

*git push origin --delete existing_branch_name*

**Слияние двух веток**

*git merge existing_branch_name*

*git merge --no-ff existing_branch_name*

**Отображение журнала фиксации в виде графика для текущей или всех веток**

*git log --graph --oneline --decorate*

*git log --all --graph --oneline --decorate*

**Прекращение слияния при конфликте**

*git merge --abort*

*git reset*

**Добавление удалённого репозитория**

*git remote add awesomeapp https://github.com/someurl..*

**Просмотр удалённых URL-адресов**

*git remote -v*

**Получение дополнительных сведений об удалённом репозитории**

*git remote show origin*

**Отправка изменений в удалённый репозиторий**

*git push origin main*

**Получение изменений из удалённого репозитория**

*git pull*

*git pull --verbose*

**Слияние удалённого репозитория с локальным**

*git merge origin*

**Отправка новой ветки в удалённый репозиторий**

*git push -u origin new_branch*

**Удаление удалённой ветки**

*git push --delete origin existing_branch*

**Использование перебазирования**

*git rebase branch_name*

**С подробным описанием команд можно ознакомиться здесь:**

*https://habr.com/ru/company/ruvds/blog/599929/*


**Для более полного усвоения информации о работе с Git можно воспользоваться тренажёром по ссылке:**

*https://learngitbranching.js.org/?locale=ru_RU*