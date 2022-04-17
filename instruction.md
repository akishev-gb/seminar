# Инструкция по работе с Git

## Начальные настройки и установки

Чтобы зарегистрироваться в Git, надо представиться, для этого в терминале последовательно вводим две строки:
><code>*git config --global user.name «Ваше имя английскими буквами»*</code>

><code>*git config --global user.email ваша почта@example.com*</code> 
>>Пример:
>>
>><code>*git config --global user.name IvanIvanov*</code>
>>
>><code>*git config --global user.email ivanov_ip@yandex.ru*</code>

><code>*git init*</code> – **инициализация локального репозитория в созданной и открытой в VSCode папке**

><code>*git status*</code> – **получить информацию от git о его текущем состоянии**

 Для сохранения изменений в файле, их необходимо закоммитить. Но сначала надо обозначить эти файлы для Git, при помощи команды <code>*git add*</code>, добавляющей (или подготавливающей) их к коммиту.

><code>*git add name_file*</code> – **добавить файл или файлы к следующему коммиту**

>><code>*git reset name_file*</code> - **исключить добавление файла к следующему коммиту**

>>>![git add and reset](images/git%20reset.png)

><code>*git commit -m “message”*</code> – **создание коммита**.

><code>*git log*</code> – **вывод на экран истории всех коммитов с их хеш-кодами**

>>>![git log](images/git%20log.png)

>><code>*git log --graph*</code> – **вывод на экран древовидной истории всех коммитов с их хеш-кодами**

>>>![git log graph](images/git%20log%20graph_1.png)
>>>![git log graph](images/git%20log%20graph_2.png)

><code>*git checkout*</code> – **переход от одного коммита к другому**


><code>*git checkout* master </code>– **вернуться к актуальному состоянию и продолжить работу**

><code>*git diff*</code> – **увидеть разницу между текущим файлом и закоммиченным файлом**

>><code> *git diff 5a286..f8be5*</code> 
 **увидеть разницу между двумя коммитами, используется команда diff (с указанием промежутка между коммитами)**

 >>>![git diff](images/git%20diff.png)

## Работа с ветками

><code>*git branch*</code> – **посмотреть список веток в репозитории**

>>>![git branch](images/git%20branch.png)

><code>*git branch <название ветки>*</code> – **создать новую ветку**

><code>*git checkout <название ветки>*</code> – **переход к другой ветке**

>>>![git checkout](images/git%20checkout.png)

><code>*git branch -d <название ветки>*</code> – **удалить ветку**

## Работа с удаленными репозиториями

><code>*git clone <ссылка>*</code> - **клонировать репозиторий из удаленного источника**

><code>*git push* </code>- **отправка изменений на удаленный репозиторий**

><code>*git pull* </code>- **команда для подгрузки изменений из удаленного репозитория**

><code>*git remote add origin <ссылка>*</code> - **привяка локального репозитория к удаленному репозиторию**
