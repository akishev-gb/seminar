# Инструкция по работе с системой контроля версий Git

## команды для работы с системой Git

*git init* - **команда для создания локального репозитория.**

```sh
PS D:\Giit> git init
Reinitialized existing Git repository in D:/Giit/.git/
```

*git status* - **команда проверки статуса версионности репозитория.**

```sh
PS D:\Giit> git status
On branch master
nothing to commit, working tree clean
```

*git add* - **команда для добавления версионности к файлам репозитория.**

```sh
PS D:\Giit> git add .\instraction.md
```

*git commit(-m "сообщение")* - **команда для добавления в репозиторий отслеживаемых файлов.**

```sh
PS D:\Giit> git commit -m "add instruction1"
[master 7907cb7] add instruction1
 1 file changed, 22 insertions(+)
```


*git diff* - **команда для вывода различий между версиями.**

```sh
PS D:\Giit> git diff
diff --git a/instraction.md b/instraction.md
index 16879dd..bb7a1aa 100644
--- a/instraction.md
+++ b/instraction.md
@@ -36,6 +36,15 @@ PS D:\Giit> git commit -m "add instruction"

 *git log* - **команда для вызова журнала изменений**

+```sh
+PS D:\Giit> git log
+commit 7907cb78d652a027a58ed30cefbb466a00ca9057 (HEAD -> master)
+Author: Nik Krav <marshaque666@gmail.com>
+Date:   Wed Feb 16 21:03:01 2022 +0300
+
+    add instruction1
+```
+
 *git checkout (параметр)* - **команда для перемещения по изменениям**
```

*git log* - **команда для вызова журнала изменений.**

```sh
PS D:\Giit> git log
commit 7907cb78d652a027a58ed30cefbb466a00ca9057 (HEAD -> master)
Author: Nik Krav <marshaque666@gmail.com>
Date:   Wed Feb 16 21:03:01 2022 +0300

    add instruction1
```

*git checkout (параметр)* - **команда для перемещения по изменениям.**

```sh
PS D:\Giit> git checkout 7907c     
Previous HEAD position was aeb7286 add commands
HEAD is now at 7907cb7 add instruction1
```

### Визуализация использования основных команд Git для управления проектом.
![Жизненний цикл файлов](https://autogear.ru/misc/i/gallery/48362/1780759.jpg)