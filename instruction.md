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

# Commands for remote repo

*git clone* - **for cloning remore repo**

*git push* - **upload changes into remote repo**

*git pull* - **download changes to remote repo**

*git remote add origin https://github.com/hvtee/ID* - **create remote repo**

*git branch -M main* - **rename branch to main**