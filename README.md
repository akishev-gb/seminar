![Эмблема git](git_label.png)
# Инструкция по работе с системой контроля версий Git

_**[Официальный сайт Git](https://git-scm.com)**_

## История

Ядро Linux — это достаточно большой проект с открытым исходным кодом. Большую часть времени разработки ядра Linux (1991–2002 гг.) изменения передавались между разработчиками в виде патчей и архивов. В 2002 году проект ядра Linux начал использовать проприетарную децентрализованную СКВ BitKeeper.

В 2005 году отношения между сообществом разработчиков ядра Linux и коммерческой компанией, которая разрабатывала BitKeeper, прекратились, и бесплатное использование утилиты стало невозможным. Это сподвигло сообщество разработчиков ядра Linux (а в частности Линуса Торвальдса — создателя Linux) разработать свою собственную утилиту, учитывая уроки, полученные при работе с BitKeeper. 

Торвальдс так саркастически отозвался о выбранном им названии git (что на английском сленге означает «мерзавец»):

>I'm an egotistical bastard, so I name all my projects after myself. First Linux, now git. (Я эгоистичный ублюдок, и поэтому называю все свои проекты в честь себя. Сначала Linux, теперь git.)


## Настройки

*git config --global user.name "User_name"* - **настройка имени пользователя, которое будет использоваться при создании коммита**

*git config --global user.email "example@mail.com"* - **настройка e-mail, который будет использоваться при создании коммита**

*git init* - __создание репозитория__

## Состояния файлов


*__Жизненный цикл файлов в системе контроля версий git__*
![Жизненный цикл файлов в системе git](file_states.png)

В системе git файлы могут быть неотслеживаемые и отслеживаемые. Отслеживаемые файлы могут находится в 3 состояниях: 
* не изменено (Unmodified)
* изменено (Modified) 
* подготовленное (Staged).

*git status* - **команда для просмотра состояния файлов в репозитории**


*git diff* - **команда для просмотра различий между изменениями**
## Команды для работы с индексом 

*git add .* или *git add имя_файла*  - **команда для добавления изменений или файлов в отслеживании**

*git add file.name* — __команда добавляет файл в "отслеживаемый" и делает готовым для коммита__

*git add .* — __команда делает все измененные файлы готовыми для коммита__

_git add '*.txt'_ — __команда добавляет файлы по маске__

*git commit -m "message"* - **команда для закрепления изменений в репозиторий**

*git log* - **команда для вывода журнала изменений**

*git log --graph* - **команда для вывода журнала изменений c графическим отображением веток**

*.gitignore* - **файл, в котором указываются файлы и каталоги, ингорируемые Git, файл необходимо добавить в репозиторий**

## Ветви

*git branch* - __команда для вывода списка веток__

*git branch branch_name* - __команда для создания ветки__

*git chechout branch_name* - __команда для переключения между ветками__

*git branch -d branch_name* - __команда для удаления ветки__

*git chechout -b branch_name* - **команда для создания ветки и переключения на нее**

*git chechout bc23c* - **команда переключения на коммит с указанным хешем**

*git branch branch_name* - __команда для слияния текущей ветки и ветки branch_name в текущую ветку__

## Работа с удаленным репозиторием

*git clone repository_url* - **скачать удаленный репозиторий в локальный**

### Работа со своим удаленным репозитарием

1. Авторизоваться на сайте (например, github.com)
2. Создаем свой репозитарий
3. Вводим команды:
    * *git remote add origin repository_url*  - __устанавливаем подключение к удаленному репозиторию__
    * git branch -M master - __создаем локально ветку__
    * git push -u origin master - __устанавливается связь между той веткой, в которой находимся с веткой master на удалённом сервере. Команду требуется выполнить единожды, чтобы потом можно было отправлять/принимать изменения лишь выполняя git push/git pull__

*git push* - __отправляем изменения в удаленный репозиторий__
*git pull* - __принимаем изменения с удаленного репозитория__