# Instruction for GIT

## start a working area (see also: git help tutorial)

* init      Create an empty Git repository or reinitialize an existing one

(Создайте пустой репозиторий Git или повторно инициализируйте существующий)

---

## work on the current change (see also: git help everyday)

* add       Add file contents to the index

(добавить файлы к отслеживанию)

```
git add .\File_nelper_for_GIT
git commit -m "initial commit"
```

* mv        Move or rename a file, a directory, or a symlink

(Переместить или переименовать файл, каталог или символическую ссылку)

* restore   Restore working tree files

(Восстановить файлы рабочего дерева)

* rm        Remove files from the working tree and from the index

(Удалить файлы из рабочего дерева и из отслеживания)(нифига чет не работает)

---

## grow, mark and tweak your common history

* branch    List, create, or delete branches

(Список, создание или удаление ветвей)

* commit    Record changes to the repository

(Записать изменения в репозиторий)

* merge     Join two or more development histories together

(объединить две или более истории развития вместе)

* rebase    Reapply commits on top of another base tip

(перезаписывает, совершает коммит поверх другого)

* reset     Reset current HEAD to the specified state

(Сбросить текущий HEAD в указанное состояние)

* switch    Switch branches

(Переключить ветки)

* tag       Create, list, delete or verify a tag object signed with GPG

(Создать, перечислить, удалить или проверить объект тега, подписанный с помощью GPG)

---

## collaborate (see also: git help workflows)

* clone     Clone a repository into a new directory

(Скачивание удалённого реопзитория на локальный компьютер)

![comand clone](./Clone.PNG)

* pull      Fetch from and integrate with another repository or a local branch

(Скачивание измениний с удалённого репозитория на локальный компьютер)

* push      Update remote refs along with associated objects

(Отправка или фиксация изменений на удалённый репозиторий

![image to push comand](./Git_puch.PNG)

---

## Terminal

* cd       + имя репозитория, это команда для перемещения в другой репозиторий