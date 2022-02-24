# Репозиторий для пул реквестов

# Инструкция по работе в системе контроля версий 
![начало работы](гит.jpg)
## Команды для работы в системе контроля версий Git

*git init* - **команда инициализации репозитория локально**

Больше информации здесь: [создание репозитория](https://git-scm.com/book/ru/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-Git-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F)

*git add* - **команда для добавления изменений или файла в отслеживание**
> *git add* требует введения имени файла или .\ для добавления всех файлов репозитория одновременно
>> чтобы ввести имя файла, достаточно вбить первые 2 буквы + Tab

*git commit -m "some message"* - **команда для закрепления изменений в репозитории**
> сообщение должно отображать реальные изменения для упрощения навигации по коммитам

*git log* - **команда для вывода журнала изменений**
> часто для возвращения из журнала обратно к работе в терминале нужно ввести **q**

Больше информации здесь: [просмотр истории коммитов](https://git-scm.com/book/ru/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80-%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B8%D0%B8-%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D0%BE%D0%B2)

*git status* - **команда для просмотра локальных изменений**

*git diff* - **команда для просмотра различий между изменениями**
> не покажет изменения до сохранения рабочей версии с помощью Ctrl+S

*git checkout* - **команда для перемещения между коммитами и между ветками**
>для вызова одной изпредыдущих версий достаточно ввести первые 4 символа названия версии из журнала
>> для возвращения к работе с последней версией необходимо ввести *git checkout master*

## Команды для работы с ветвлением

![ветвление](branch.jpg)

*git branch* - __команда для вывода списка веток__
> звездочкой и зеленым цветом выделена текущая ветка, с которой происходит работа в данный момент

*git branch branch_name* - __команда для создания новой ветки__

*git checkout branch_name* - __команда для переключения между ветками__

*git branch __-d__ branch_name* - __команда для удаления ветки__
> *git branch __-D__ branch_name* - осуществляет безоговорочное удаление, не учитывая наличие изменений в ветке

*git merge branch_name* - __команда для слияния веток__
> Если в случае слияния происходит __конфликт__, необходимо решить его одним из способов:
* *Accept current change* - сохранить данные исходной ветки
* *Accept incoming change* - сохранить данные входящие из вливаемой ветки
* *Accept both changes* - сохраняем обе версии данных
* *Compare changes* - сравниваем две версии и сохраняем выборочно 

*git checkout -b branch_name* - __команда для создания новой ветки и перехода на нее__

Больше информации здесь: [ветвление, начало](https://git-scm.com/book/ru/v2/%D0%92%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-Git-%D0%9E-%D0%B2%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B8-%D0%B2-%D0%B4%D0%B2%D1%83%D1%85-%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%85)

## Команды для работы с удаленными репозиториями

*git clone ссылка-на-удаленный-репозиторий* - __команда для копирования удаленного репозитория на компьютер__
> для работы в скопированной папке необходимо в нее перейти: cd .\название диска\
> для внесения изменений\предложения изменений в чужой репозиторий необходимо:
* создать на GitHub fork интересующего нас репозитория
* сделать *git clone* нашей версии репозитория
* создать _ветку_ с предлагаемыми изменениями
* производить все изменения только в этой ветке
* отправить - *git puch* - эти изменения в свой аккаунт
* В окне на GitHub появится возможность сделать Pull request

*git push* - __команда для отправления изменений локального репозитория на удаленный (на GitHub)__
> при этом может потребоваться авторизоваться на удаленном репозитории

*git pull* - __команда для скачивания актуального состояния из удаленного репозитория в связанный с ним локальный репозиторий__
> Чтобы связать удаленный репозиторий на GitHub с локальным репозиторием нужно:
* Создать локальный репозиторий
* СОздать новый удаленный репозиторий на GitHub
* "Подружить" ваш локальный и удаленный репозитории. GitHub при создании нового репозитория подскажет, как это можно сделать. 
* Отправить (push) ваш локальный репозиторий на удаленный репозиторий на GitHub