![](https://fuzeservers.ru/wp-content/uploads/3/0/c/30c29ce4cc08523ecc6e1f205bc207d0.jpeg)

# Инструкции по работе с GIT

>## GIT: Базовые команды

## 1. *Регистрация пользователя:*

1. *git config --* - **git config --global user.name «Your name»**

2. *git config --global user.email example@example.com* - **Введите e-mail**

## 2. *Другие команды:*

* *git --version* - **Версия Git**

* *git init* - **создание локального репозитория**

* *git status* - **вывод статуса системы на данный момент**

* *git add* - **Добавляет версионность файлу**

* *git commit -m* **Фиксирует версию файла (создаёт коммит)**

* *git diff* - **просмотр изменений в двух последних ветках**

* *git log* - **Вывод версий в хронологическом порядке**

* *git checkout <Хэш номер коммита или название_ветки>* - **Переключает между различными зафиксированными версиями или ветками файла**

## 3. Команды по ветвлению

![e.g.:](https://miro.medium.com/max/1838/1*yayarC3GxDRDkU6l3dWuYw.png "ветвление")

* *git branch* - **команда для показа списка веток**

* *git branch <branch_name>* - **команда для создания новой ветки**

* *git checkout <branch_name>* - **переход на ветку branch_name**

* *git branch -d <branch_name>* - **удалить уже слитую ветку**

* *git merge <branch_name>* - **слить данные в текущею ветку из ветки branch_name**

* *git log --graph* - **вывод журнала в графической последовательности**

### 3.1 *Вспомогательные команды:* 

* *git branch -d < branch name >*  **Удаляет ветку по имени**

* *git branch -m <branch_name>*  **переименование основной ветки**

## 4. Команды для удаленного репо

* *git clone <ссылка>* - **Клонирование репо по ссылке**

* *git push* - **отправка данных на удаленный репо**

* *git pull* - **стягивание данных с удаленного репо** 

## <span style="color:green"> *Recommended sequence of commands:* </span>

|Первая   |Вторая   |Третья|Четвёртая|
|----------|-----------|---------|------------|
|git status|git add    |git status  |git commit -m

>![e.g.:](https://ie.wampi.ru/2022/10/02/ss-git-status.jpg "Example")

## <span style="color:orange"> *Unrecommended commands for novice/begginer:*</span>
* *git pull* - **Стягивает фиксацию с репозиториев**

* *git fetch* - **Собирает все коммиты с целеврой ветки которые не находятся в текущей и записывает их в локальный репо (не добавляет в ветку master)**

* *git merge <merged brunch>* - **Сливает изменения из "сливаемой ветки" в текущую ветку**

### *Доп. инфо:*

> *Воспользуйтесь для получения доп. информации* [документацией по GIT](https://git-scm.com/doc)

>*Для тренировки и обучению по GIT используйте* [онлайн-тренажёр](https://learngitbranching.js.org/)

> *git help* - **для вывода списка различных git команд**

> cм. *README* файл для информации