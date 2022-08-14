# Инструкция по работе с GIT

# Базовые команды

*git init* – **инициализация локального репозитория**

*git status* – **получить информацию от git о его текущем состоянии**

*git add* – **добавить файл или файлы к следующему коммиту**

*git commit -m “message”* – **создание коммита.**

*git log* – **вывод на экран истории всех коммитов с их хеш-кодами**


# Команды по ветвлению

*git branch* - **команда для показа списка веток**

*git branch <branch_name>* - **команда для создания новой ветки**

*git checkout <branch_name>* - **переход на ветку branch_name**

*git branch -d <branch_name>* - **удалить уже слитую ветку**

*git merge <branch_name>* - **слить данные в текущею ветку из ветки branch_name**

*git log --graph* - **вывод журнала в графической последовательности**

## Commands for remote repository

*git clone* - **clone remote repository to local comp**

*git push* - **send changes from local comp to remote repository**

*git pull* - **send changes from remote repository to local comp**

*git remote add origin* - **fix the branch in remote repository**

*git branch -M branch_name* - **change the name of main branch**