# Инструкция по работе с GIT

# Базовые команды

* git status  **показать состояние репозитория**

* git diff   **сравнить рабочую директорию и индекс** 

* git diff **--color-words  # сравнить рабочую директорию и индекс, показать отличия в словах** 

* git diff index.html  **сравнить файл из рабочей директории и индекс**

* git diff HEAD  **сравнить рабочую директорию и коммит, на который указывает HEAD**

* git diff **--staged  сравнить индекс и коммит с HEAD**

* git diff **master feature # посмотреть что сделано в ветке feature по сравнению с веткой master**

* git diff **--name-only master feature # посмотреть что сделано в ветке feature по сравнению с веткой master, показать только имена файлов**

git diff master **feature # посмотреть что сделано в ветке feature с момента (коммита) расхождения с master**

*git branch* - **команда для показа списка веток**

*git branch <branch_namea>* - **команда для создания новой ветки**

*git checkout <branch_name>* - **переход на ветку branch_name**

*git branch -d <branch_name>* - **удалить уже слитую ветку**

git merge <branch_name>* - **слить данные в текущую ветку из ветки branch_name**

*git log --graph* - **вывод журнала в графической последовательности**

*testing merge command* 

## Команды для удаленного репозитория

*
*
*
