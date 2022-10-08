# Инструкция по работе с Git

![Логотип Git](Git-Logo-2Color.png)

>Логотипы Git можно скачать по ссылке: https://git-scm.com/downloads/logos

## Базовые команды при работе с Git

*git --version* - **Версия системы Git**

*git config --global user.name «Ваше имя английскими буквами»* - **Ввод имени в систему**

*git config --global user.email ваша почта@example.com* - **Ввод электронной почты**

*git init* - **Инициализация локального репозитория**

*git status* - **Вывод состояния системы на данный момент**

*git add* - **Добавление версионности файлу**

*git add . ***или*** git add --all* - **Добавление версионности всех файлов проекта**

*git commit -m <Same_message>* - **Добавление файлов к коммиту (сохранение)**

*git diff* - **Команда для вывода разницы между последним коммитом и текущими изменениями**

*git log* - **Вывод списков коммитов в хронологическом порядке**

*git checkout <хеш-номер коммита или master>* - **Переключение между различными коммитами**

## Последовательность ввода команд для создания ***коммита*** файлу

* *git status*
* *git add*
* *git status*
* *git commit -m <Same_message>*
* *git log*

## Команды по ветвлениям

*git branch* - **Просмотр всех веток в репозитории**

*git branch <branch_name>* - **Создание новой ветки**

*git checkout <branch_name>* - **Переключение на ветку <branch_name>**

*git checkout -b <branch_name>* - **Создание и сразу переключение на ветку <branch_name>**

*git merge <branch_name>* - **Слияние веток <branch_name>**

*git branch -d <branch_name>* - **Удаление веток <branch_name>**

*git log –graph* - **Графическое отображение сделанных коммтов**

## Последовательность ввода команд для создания ***ветки*** и перехода в нее для работы

+ *git branch*
+ *git branch <branch_name>*
+ *git branch*
+ *git checkout <branch_name>*
+ *git branch*
---

***или***

---
+ *git branch*
+ *git checkout -b <branch_name>*
+ *git branch*

> ***Внимание:*** Создание подветок из дочерних веток **крайне** не рекомендуется.

## Работа с файлом .gitignore

1. В папке создать файл ***.gitignore***.
2. В файл ***.gitignore*** вводятся наименования файлов, которые не должны отслеживаться _Git_.
3. Добавляем версионность файлу ***.gitignore*** с помощью команды *git add .gitignore*.
4. Добавляем файлу  ***.gitignore*** коммит с помощью команды *git commit -m "Добавлен gitignore файл"*.

## Полезные ссылки

|Номер|Ссылка                          |Описание                 |
|-----|--------------------------------|-------------------------|
|1    |https://git-scm.com/download/win|Ссылка для скачивания Git|
|2    |https://gb.ru/posts/soveti-pro-git|Советы для тех, кто осваивает Git|
|3    |https://habr.com/ru/post/541258/|Git для новичков (часть 1)|
|4    |https://habr.com/ru/post/542616/|Git для новичков (часть 2)|


![Логотип Git](Git-Logo-1788C.png)