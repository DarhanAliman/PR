1. Для перемещения по директориям использется команда *cd*
```bash
$ cd
```
2. Чтобы узнать текущую (рабочую) директорию используется команда *pwd*
```bash
$ pwd
``` 
3. Чтобы просмотреть содержимое директории используется команда *ls*
```bash
$ ls
``` 
4. Чтобы просмотреть все скрытые элементы директории, применяется команда *ls -a*
```bash
$ ls -a
```
5. Чтобы создать файл, используется команда *touch*
```bash
$ touch %Имя_Файла%.Расширение
```
6. Чтобы создать директорию, используется команда *mkdir*
```bash
$ mkdir %Имя_Директории%
```
7. Чтобы создать несколько директорий сразу, применяется команда *mkdir -p*
```bash
$ mkdir -p %Имя_Директории1% %Имя_Директории2%
```
8. Чтобы скопировать файлы, применяется команда *cp* 
```bash
$ cp %что_копируем% %куда_копируем%
```
9. Чтобы переместить файл из одной директории в другой, используется команда *mv*
```bash
$ mv %что_перемещаем% %куда_перемещаем%
```
10. Чтобы просмотреть содержимое файла, используется команда *cat*
```bash
$ cat %имя_файла%
```
11. Чтобы скопировать содержимое файла в буфер обмена, используется команда *clip*
```bash
$ clip < %имя_файла%
```
12. Чтобы удалить файл, применяется команда *rm*
```bash
$ rm %имя_файла%
```
13. Чтобы удалить директорию, применяется команда *rmdir*
```bash
$ rmdir %имя_директории%
```
14. Чтобы удалить директорию, в которой что-то содержится, используется команда *rm -r* 
```bash
$ rm -r
```
15. Чтобы выполнить несколько команд друг за другом, применяется *$$*
```bash
$ %команда1% && %команда2%
```
16. С помощью ↑↓ можно перемещаться по использованным ранее командам
17. Tab применяется для автозаполнения или предложения вариантов команд
18. / и ~ позволяют перемещаться к корневой и домашней директориям 
19. Для инициализации локального репозитория, испольуется команда *get init*
```bash
$ git init
```

--------


Позволяет инициализировать локальный репозиторий


```bash
rm -rf .git
```
Позволяет разгитить папку


```bash
git status
```
Позволяет проверить состояние репозитория


```bash
git add
```
Позволяет подготовить файл к сохранению


```bash
git add --all
```
Нужно, чтобы подготовить все файлы к сохранению


```bash
git add .
```
Добавить в репозиторий текущую папку со всеми эелементами


```bash
git commit -m
```
Позволяет сделать коммит и указать сообщение, в котором описываются изменения


```bash
git log
```
Позволяет просмотреть историю коммитов


```bash
git remote add
```
Нужно, чтобы связать локальный репозиторий с удалённым


```bash
git remote -v
```
Позволяет убедиться, что репозитории связаны


```bash
ssh-keygen
```
Позволяет сгенерировать ssh-ключ




