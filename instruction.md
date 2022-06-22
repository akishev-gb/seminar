# Инструкция по работе с Git


## Начальные настройки и установки

>### ***git config --global user.name «Ваше имя английскими буквами»** например: Konstantin*

>### ***git config --global user.email «ваша почта@example.com»***

## Основные комманды

> ### *git --version* - **вывод версии системы контроля версий**

Пример:

![gitVersion](https://sun9-19.userapi.com/s/v1/ig2/iyrE_b8k4_WyJKLytUf8cY2M1wMhlI49xhU-Xrw4eDtDWa5ojfKFstLDtmp2w5UweU3ceJfTAwYor6GMYly_qem-.jpg?size=399x68&quality=95&type=album)

> ### *git init* - **Инициализация пустого репозитория**

Пример:

![git_Initialization](https://sun9-6.userapi.com/s/v1/ig2/-VqZZN5FliwdYthG3OMxkd_c9JbNM60MAtQRWTE_MRGUwl4SHv_kPXBNNfSorSlSyLB95wXgBpPF5w4p8krLIndA.jpg?size=541x56&quality=95&type=album)

> ### *git status* - **комманда для проверки статуса GIT**

Примеры:

* Использование в новой папке:

 ![git_status_new_folder](https://sun9-2.userapi.com/s/v1/ig2/asRrTgUsYUI7O71cViQpUtC7qbPwX8QMgzArEc2TU9LcGPvD4gTL0hvZ1gUaGnjDcRbir2ig0HASsOQKSkVTq0Lu.jpg?size=463x124&quality=95&type=album)

* Исльзование не изменяя файлы:

![git_status_nothing_to_commit](https://sun9-26.userapi.com/s/v1/ig2/TdBYFeScLDr2uuxvFtQG4lcFZoYFiPXB1f4EbGaLEv9w4Ew32UlfmUZ5QnPboMRCAy2N7Wcx7lDsN1X6Yphn-2Z3.jpg?size=357x69&quality=95&type=album)

* Использование при новых/изменённых файлах:

![git_status_new_and_modified_files](https://sun9-46.userapi.com/s/v1/ig2/s38vlgJvZmaSsF6vIMi2pTg8--9-Jy7TZUkC_A0QXUIamJP04k3in71U2LDLSzjSWBguh55cXnMRtoTI9HF4NzBo.jpg?size=506x224&quality=95&type=album)

 * Использование при сохранённых, но не зафиксированных файлах:
 
  ![git_status_saved_not_commited_file](https://sun9-2.userapi.com/s/v1/ig2/8XBYcRycj5KRAfYuoW9gKp3sMwnH7W0a4IFUpWCN-RBpDvUPXaxERPnFfKAUZ1tGo-V6KcoDFx-Pq3RTXEkK9ArR.jpg?size=361x123&quality=95&type=album)

> ### *git add* - **комманда для добавления файлу версионности**

Если всё правильно, то гит ничего не показывает.

> ### *git commit -m "message"* - **фиксация изменений в сохранение**

Пример:

![git_commit](https://sun9-79.userapi.com/s/v1/ig2/Tf2ky5A4UMI3mZSEvKtwx6rz1JmIqEPY8yY_cJbwkyqsoO4jtMLq-FoXY8a-0Szc50j3VrRqjlYPi8OimGVqreAh.jpg?size=476x89&quality=95&type=album)

> ### *git log* - **вывод журнала коммитов**

Для выхода из журнала нажми клавишу "Q"

Пример

![git_log](https://sun9-84.userapi.com/s/v1/ig2/OMQNYUr2J4ol84F1xepqQBWul2NNhqOzUCfWzf9cpmJDTmQqXimIkkzjJw04FvP7HueIcMCrdftb9t5X-nfm4bAe.jpg?size=473x123&quality=95&type=album)

> ### *git diff* - **показ отличий между коммитами**

Пример

![git_diff](https://sun9-80.userapi.com/s/v1/ig2/zXV_Ii6-BgprSCuHenm4wMQzcMjgQrnfE2WHSDSci2EOeJYK-E82QVRfVYgC-tYN357odFyvd_NVUnQfhK-gp9O3.jpg?size=330x155&quality=95&type=album)

> ### *git chekout <хэш-номер коммита>* - **переход на определённый коммит**

Пример:

![git_checkout](https://sun9-47.userapi.com/s/v1/ig2/YwDTsZEjeAdt_OA6WRfhsMptludF4iGFve4wprwpZvi9FLEpl6GrfItsWLSmCGA4EVK82aZAZyxIMMoHuzke0iWD.jpg?size=549x345&quality=95&type=album)

> ### *git checkout master* - **переход на актуальную рабочую версию**

Пример:

![git_checkout_master](https://sun9-82.userapi.com/s/v1/ig2/ZbNHmm4eqrbOjK4Hp6pf6g0CtTNOp9iKocfKHwWKL11nWqNN44TLO6Zmy2a8ZrooKd3OJKNQ7JnJmZ6Dwof50XXo.jpg?size=411x77&quality=95&type=album)

## Команды для работы с ветвлением 

>### *git branch* - **вывод всех веток на экран**

* Пример:

![branches](https://sun9-63.userapi.com/impg/I7pcH-WwBXTfzEbNstrd_IArhwYJ36DdbolyKA/DGoSO6eLiEo.jpg?size=365x120&quality=95&sign=598d1b7f091cd5dcf6ebc139aab25dc0&type=album)

>### *git branch "branch_name"* - **создание новой ветки**

* Опять же, если всё хорошо, то git ничего не покажет. Проверить создание ветки можно при помощи ***git branch***

>### *git checkout -b "branch_name"* - **создание и переключение на новую ветку**

* Пример:

![checkout on new branch](https://sun9-12.userapi.com/impg/4UjGCff7MwLCQ_EJufPllOddm8FRN5eL0UZbSw/NxOa2PCmvas.jpg?size=439x174&quality=95&sign=a4a6b5e8d3936724b1e5b0358ce3d7e5&type=album)

>### *git checkout "branch_name"* - **переключение на новую ветку**

* Пример:

![checkout on already exist branch](https://sun9-40.userapi.com/impg/xgPRLmQviNb_wAFZfUnBTDu8DL29FIBwjWbX3w/6LkDpsdDTMM.jpg?size=416x191&quality=95&sign=08c354053101be1b78d8f2bff6d6ec6e&type=album)

>### *git merge "branch_name" - **слияние веток**

* Пример без конфликта:

![merge](https://sun9-85.userapi.com/impg/LuAdIFTMICuxVd6ZhveV5iFCzJg4Cqbn-fK12A/bFcvfm5Ckk8.jpg?size=394x107&quality=95&sign=f637a54c482f22a26662222b6c285922&type=album)

* При слиянии может возникнуть конфликт, и вот как это будет выглядеть в терминале:

![merge_conflict](https://sun9-31.userapi.com/impg/jQv3GpjfQ2kmoG71XeZ9SuTWKc80AwUIuibl3Q/j9UsXKn2Up4.jpg?size=466x91&quality=95&sign=8dcb18a11a8a0d21876758d2e44aa050&type=album)

>### *git branch -d "branch_name* - **удаление ветки**

* Пример:

![delete branch](https://sun9-79.userapi.com/impg/lRIus2CWuTfS0FcvvySpso2a0T4h28yaq0KODA/EW62wrEjLfI.jpg?size=418x53&quality=95&sign=fbfc85a41e2b7a016a40d01ae7d3ee8a&type=album)

>### *git log --graph* - **вывод истории коммитов с визуализацией**

* Пример:

![git log](https://sun9-71.userapi.com/impg/IfVh4g7MyqJmjwBbV0YLnIXnp0uTU2_TC5HQUA/dL5plAQXxMY.jpg?size=551x441&quality=95&sign=021ff133a30d4ce957a1727b53ca1825&type=album)
