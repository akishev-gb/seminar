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

## Команды для удалённого репозитория

*git clone* - **клонирование уаленного репо на локальный компьютер**

*git push* - **отправка изменений с локального компьютера на удалённый репо**

*git pull* - **стягивание изменений с удалённого репо на локальный компьютер и их применение**

*git remote add origin* - **фиксация ветки в удалённом репозитории**

*git branch -M <branch_name>* - **изменеие название основной ветки**

# Как вставить изображения и ссылки

*вставка локального изображения* - Вам нужно только указать путь к изображению в скобках базовой грамматики

! [VScode](D:\КУРСЫ\IT\vscode.jpg)

>Для того, чтобы картинка отображалась в окне предварительного просмотра, саму картинку перевести в текстовый формат base64 и вставить внутрь тега img в заметках. Для этого можно:

>- На сайте https://www.base64-image.de/ загрузить картинку и получить код base64

>- Нажать "Show code", потом "copy to clipboard" для кода в "For use in <img> elements"

>- В текст заметки прописать < img src="XXX" /> , где вместо XXX вставить скопированный код

>- Все, в свойствах задачи должна появиться картинка!

*вставка сетевого изображения* - нужно только заполнить сетевую ссылку изображения в скобках базовой грамматики

! [git](https://yandex.ru/images/search?from=tabbar&text=git&pos=0&img_url=http%3A%2F%2Ffuzeservers.ru%2Fwp-content%2Fuploads%2F3%2F0%2Fc%2F30c29ce4cc08523ecc6e1f205bc207d0.jpeg&rpt=simage&lr=193)

<<<<<<< HEAD
<<<<<<< HEAD
! [Хакер](112_2022_03_21_1_.jpg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/rERnNXCdFqs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

 https://gist.github.com/Jekins/2bf2d0638163f1294637#Blockquotes
 
> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
