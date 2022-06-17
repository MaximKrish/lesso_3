# Инструкция по работе GIT


## Команда создающая локальный репозиторий
```sh 
git init
```

## Добавление файла  в локальном репозитории
```sh 
git add имя_файла
```
## Команда  фиксирующая изменения и сообщает о появлении новых версий файлов
```sh 
git commit - m "Пишем изменения котрые хотим зафиксировать"
```

## Команда показывающая разницу между текущей и уже зафиксированной версией файла
```sh 
git diff
```

## Команда выводит список всех коммитов (сохранений) в хронологическом порядке
```sh 
git log
```

##  команда позволяющая перемещаться между сохранениями
```sh 
git checkout
```


## Папка для игноривания файлов

```sh 
.gitignore
```
**прописываем имена файлов которые необходимо игнорировать**

## Команда добавления рисунков
```sh 
![ текст, будет отображаться если картинка не дочтупна] ( имя файла)
```
![Таблица](tabl1.jpg)

## Обрамляется полужирный текст в языке Markdown?

```sh 
**с обеих сторон без пробелов**
```
## Посмотреть список веток

```sh 
git branch
```
 комманда показывает  ветки

 ## Создает новую ветку

```sh 
git branch имя_ветки
```
Данная комманда создает новую ветку 

## Удаляет ветку

```sh 
git branch -d имя_ветки
```
Данная комманда удаляет ветку 
 ## Удалить ветку

```sh 
git branch -d имя _файла
```
 комманда удаляет не нужные ветки

  ## Переход на другие ветки

```sh 
git checkout имя _ветки
```
 комманда перехода на нужныю ветку

git config --list
! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/MaximKrish/lesso_3.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
## Набираем git pull --rebase
