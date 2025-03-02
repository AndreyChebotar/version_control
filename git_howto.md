# Подсказка по  GIT

## Ссылка на скачивание GIT
[ссылка](https://git-scm.com/downloads) 


* Для начала необходимо проверить наличие GIT на Вашем ПК

```sh
git --version 
```

* Создание репозитория (инициализация)

```sh
git init
```

* Показывает текущее состояние гита, есть ли измения, которые необходимо закоммитить (сохранить)

```sh
git status
```

* Добовляет содержимое рабочего каталога

```sh
git add
```

* Сохраняет или фиксирует 

```sh
git commit (если необходимо добавить сообщение, то вводится команда git commit -m "text")
```

* Журнал изменений

```sh
git log
```

* Укороченный журнал изменений

```sh
git log --oneline
```

* Вызывание к конкретному сохранению или позволяет переключаться между версиями файла

```sh
git checkout
```

* Возвращение к коммиту, в котором ведется работа 

```sh
git checkout master или gi checkout main
```

* Разница между текущим и сохранненым файлом

```sh
git diff
``` 

* Удаление того, что еще не добавили в git

```sh
git restore
```

* Сделать копию из удаленного репозитория

```sh
git clone
```

* Скаичвание из удаленного репозитория

```sh
git pull
```

* Перенос файлов из локального репозитория на удаленный 

```sh
git push
```
