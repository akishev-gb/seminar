# Инструкция по работе с Git

## Базовые команды при работе с Git

*git version* - **версия системы Git**

*git config --global user.name «Ваше имя английскими буквами»* - **Ввод имени в систему**

*git config --global user.email ваша почта@example.com* - **Ввод эленектронной почты**

*git init* - **Инициализация локального репозитория**

*git status* - **Вывод состояния системы на данный момент**

*git add* - **Добавление версионности файлу**

*git commit -m <Some_message>* - **Добавление файлов к комиту(сохранению)**

*git diff* - **Команда для вывода разницы между последним коммитом и текущими изменениями**

*git log* - **Вывод списка коммитов в хронологическом порядке**

*git checkout <хэш-номер коммита или master>* - **Переключение между различными коммитами**

*git gelp* - **справка по всем командам**

*git rm* - **удаление файлов из индекса и рабочей копии**

*git clean* - **удаление мусора из рабочего каталога**

*git clone* - **Клонирование существующего репозитория**

*git branch* - **своего рода "менеджер веток". Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их**

*Шпаргалка для git*
<img style="display: block;-webkit-user-select: none;margin: auto;cursor: zoom-in;background-color: hsl(0, 0%, 90%);transition: background-color 300ms;" src="https://media.cheatography.com/storage/thumb/shirmik2003_git-cheat-sheet-by-samcollett-rus-wip.750.jpg?last=1577012271" width="330" height="467">

*Ссылка для шпаргалки по Git*
https://cheatography.com/shirmik2003/cheat-sheets/git-cheat-sheet-by-samcollett-rus-wip/ 

Скачать полное руководство по Git можно по ссылке
<img style="display: block;-webkit-user-select: none;margin: auto;background-color: hsl(0, 0%, 90%);transition: background-color 300ms;" src="https://git-scm.com/images/pdf.png">
https://github.com/progit/progit2-ru/releases/download/2.1.105/progit.pdf

## Команды по ветвлению

*git branch* - **просмотр всех веток в репозитории**

*git branch <branch_name>* - **создание новой ветки**

*git checkout <branch_name>* - **переключение на ветку <branch_name>**

*git merge <branch_name>* - **слияние веток <branch_name>**

* git branch -d <branch_name>* - **удаление ветки <branch_name>**

*git log --graph* - **графическое отображение сделанных коммитов**

## Команды для удаленного репозитория

*git clone <ссылка>* - **клонирование репо по ссылке**

*git push* - **отправка данных на удаленный  репо**

*git pull* - **стягивание данных с удаленного репо**

*git branch -M <branch_name>* - **переименование основной ветки**