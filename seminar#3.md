## Инструкция по работе с git:

## Что такое git:
```fix
Git — это набор консольных утилит, которые отслеживают и фиксируют изменения в файлах
```

## Первоначальная настройка
Перед началом работы с Git программа попросит вас заполнить некоторые данные о пользователе, это нужно сделать иначе вы не сможете в полной мере пользоваться программай

Для этого нужно ввести в консоли следующие команды:
```
git config --global user.name “Имя пользователя”

git config --global user.email “Ваша почта”
```


Перед началом работы с Git программа попросит вас заполнить некоторые данные о пользователе, это нужно сделать иначе вы не сможете в полной мере пользоваться программай

Для этого нужно ввести в консоли следующие команды:
```
git config --global user.name “Имя пользователя”

git config --global user.email “Ваша почта”
```

## Подготовка репозитория
Для создания репозитория необходимо ввести в консоль следующую команду:
```
git init
```

# Создание коммитов

## Команда git add
Для того чтобы добавить изменения в коммит используйте следующую команду:
```
git add <Имя файла>
```

## Просмотр состояний репозитория
Для того чтобы увидеть что в данный момент происходит с репозиторием нужно ввести в терминал следующую команжу
```
git status
```

## Создание коммитов
Для того чтобы добавить коммит необходимо ввести в терминал следующую команда:
```
git commit -m "комментарий"
```

# Переключение между коммитами

## Просмотр всех записанных коммитов
Для того чтобы посмотреть все записанные вами коммиты нужно ввести в терминал следующую команду:
```
git log
```
Данная комада выведит в терминал следующие данные:
![данные терминала](GitLogs.jpg)

## Переключение между коммитами
Для того чтобы переключиться на нужный вам коммит нужно ввести в консоль следующую команду:
```
git checkout <Имя коммита(Имя выделено жёлтым на изображении выше)>
```
