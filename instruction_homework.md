# My lecture notes

## lecture 3
git clone https://github.com/ilnar-geekbrains/version_control_lection_3.git - команда выполняет копирование репозитория по ссылке
cd .\version_control_lection_3\ - перейти в директорию version_control_lection_3
git pull - команда позволяет скачать актуальное состояние удалённого репозитория на локальный и автоматически смержить с текущей веткой
git push - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий

### Команды для переноса своего локального репозитория в онлайн репозиторий на github
git remote add origin https://github.com/eugene1284/My-first-repository.git
git branch -M main
git push -u origin main

### Как сделать pull request
Делаем копию - fork (вилка) репозитория себе в аккаунт eugene1284
git clone https://github.com/profile***/*** - перетаскиваем удалённый репозиторий себе в локальный репозиторий через 
cd repository_name - переходим в папку клонированного репозитория 
git branch new_branch_name - создаём отдельную ветку
git checkout new_branch_name - переходим в созданную ветку
вносим изменения в проект
git add .\file_name
git commit -m "добавили изменения"
git push изменения в удалённый репозиторий из локального
тыкаем кнопочку pull request на github


### Повторение
git init - инициализируем репозиторий в текущей папке
git add .\file_name - перед добавлением коммита
git commit -m "initial commit" - добавляем коммит