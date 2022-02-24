> *Репозиторий для пул реквестов*

---

# Инструкция по работе с системой контроля версий

>Инструкция написана с помощью языка разметки Markdown
>>см. информацию по языку ниже

## Основные команды

* *git init* - **команда инициализации репозитория локально**

* *git add* - **команда для добавления изменений или файла в отслеживание**

* *git commit -m "message"* - **команда для закрепления изменений в репозиторий**

* *git log* - **команда для вывода журнала изменений**

* *git status* - **команда для просмотра локальных изменений**

* *git diff* - **команда для просмотра различий между изменениями**

* *git checkout* - **команда для перемещения между коммитами и ветками**

* *git checkout master* - **команда для возвращения на актуальную версию**

## Команды для работы с ветвлением

* *git branch* - **команда для вывода списка веток**

> Существует правило, что основная работа ведется на дочерних ветках, а на ветку master лишь сливаются изменения.

* *git branch branch_name* - **команда для создания новой ветки**

> Все дочерние ветки создаются с ветки master.

* *git checkout branch_name* - **команда для переключения между ветками**

* *git checkout -b branch_name* - **создание новой ветки и переход на нее**

* *git merge branch_name* - **слияние текущей и указанной ветки**

* *git branch -d branch_name* - **удаление ветки**

> Принято удалять ветки из ветки master (хотя и из других веток удалить тоже можно).

* *git log --graph* - **команда для вывода дерева веток**

## Команды для работы с GitHub

* *git clone repository_web_address* -  **команда позволяет склонировать внешний репозиторий на наш ПК**

* *git pull* - **команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией**

* *git push* - **команда позволяет отправить нашу версию репозитория на внешний репозиторий**

> ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

### Как добавить локальный репозиторий в GitHub

**Create a new repository on the command line**

1. echo "# -" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin *web-address*
7. git push -u origin main

**Push an existing repository from the command line**

1. git remote add origin *web-address*
2. git branch -M main
3. git push -u origin main

**Import code from another repository**

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

### Как сделать pull request

1. Делаем **fork** репозитория
2. Делаем **clone** СВОЕЙ версии репозитория
3. Создаем новую ветку и в НЕЕ вносим свои изменения
4. Фиксируем изменения (делаем коммиты)
5. Отправляем свою версию в свой GitHub
6. На сайте GitHub нажимаем кнопку **pull request**

---

## Полезные ссылки

### GIT

[Шпаргалка по консольным командам Git](https://github.com/cyberspacedk/Git-commands)

[Ссылка на скачивание GIT](https://git-scm.com/)

[GitHub](https://github.com/)

### Markdown

[Справочник по Docs Markdown](https://docs.microsoft.com/ru-ru/contribute/markdown-reference)

[Материалы по Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637)