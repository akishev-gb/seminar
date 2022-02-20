# Инструкция по работе с системой контроля версий
![gitlogo](https://d.radikal.ru/d08/2202/a1/2edabfe0240c.jpg)

## Commands for working in the GIT version control system

* *git init* - **command to initialize the local repository**

* *git add* - **command to add changes or file to tracking**

* *git commit -m "some message"* - **command to commit changes to the repository**
> [!IMPORTANT]
> Старайтесь в комментарии к коммиту указывать изменения, которые были произведены в файле.
> Избегайте пустых комментариев или несвязный набор букв и/или цифр

* *git log* - **command to print change log**

* *git status* - **command to view local changes**

* *git diff* - **command to view differences between changes**

* *git checkout* - **command to move between commits and branches**

## Commands for working with branches in Git version control system

* *git branch* - __Команда для вывода списка веток__

* *git branch branch_name* - __Команда для создания новой ветки__

* *git checkout branch_name* - __Команда для переключения между ветками__

* *git checkout -b branch_name* - __Команда создания ветки и сразу переход в нее__

* *git merge branch_name* - __Команда слияния(соединения) веток__

* *git branch -d branch_name* - __Команда для удаления ветки__

> Всегда проводите команду слияния веток (git merge) из мастер ветки

![gitBranchLogo](https://a.radikal.ru/a03/2202/39/dea365c0e742.png)

[Справочник по веткам в Git](https://git-scm.com/book/ru/v2/%D0%92%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-Git-%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2%D0%B5%D1%82%D0%BA%D0%B0%D0%BC%D0%B8)

## Commands for working with GITHub in Git version control system

* ![git remote add](https://a.radikal.ru/a12/2202/b8/d3f43b78970b.png) 
   После создания удаленного репозитория, в терминале необходимо выполнить
 вот такой блок команд для связывания локального и удаленного репозиториев

  [!IMPORTANT]
> В первой команде указывайте ссылку на тот удаленный репозиторий, с которым 
> хотите связать свой локальный

[!IMPORTANT]
> Во второй и третьей строках в конце команд вместо значения "main" указывайте
> названия ваших основных(главных) веток (main, master, defoult и тд.)

* *git push* - __Команда для выгрузки содержимого с локального репозитория на
удаленный__

* *git pull* - __Команда используется для извлечения и загрузки содержимого 
из удаленного репозитория и немедленного обновления локального репозитория 
этим содержимым__

* *git clone <url>* - __Команда для получения копии Git-репозитория из адреса url__

* *git remote -v* - __Команда для отображения удаленных репозиториев, которые связаны
 с текущим локальным репозиторием__

![gitGH](https://a.radikal.ru/a22/2202/d7/6f4cb0a9734d.jpg)