# Инструкция по работе с Git

## Создание репозитория
Для создания репозитория используется команда *git init*. Для того, чтобы создать репозиторий, отройте в терминале пустую папку и в нём напишите *git init*

## Добавление файла к коммиту
Для добавления файла к новому коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием выполните команду *git add <название файла>*.

# Создание коммитов
Для того, чтобы выполнить коммит, используется команда *git commit*. Для этого в терминале с папкой-репозиторием напишите команду *git commit -m <сообщение к коммиту>*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***. Все файлы коммит должны быть предворительно добавлены

## Команды
*git status* 
Команда git status отображает состояние рабочего каталога и раздела проиндексированных файлов. С ее помощью можно проверить индексацию изменений и увидеть файлы, которые не отслеживаются Git.

*git log* За просмотр истории коммитов отвечает команда git log. В сочетании с различными параметрами эта команда выводит историю по-разному.

## Ветвление

*git branch* — создание, перечисление и удаление веток.

git branch Просто перечисляет существующие ветки, отметив активную

git branch (название ветки) Создаёт новую ветку 

git branch -d (название ветки) Удаляет ветку

*git checkout* - переключение между ветками, извлечение файлов.

git checkout (название ветки) 

*git merge* лияние веток, разрешение возможных конфликтов

git merge (название ветки для слияния)

## Клонирование репозитория 

*git clone*

git clone (ссылка на репозиторий из github.com)

## Отправка изменений на сервер

*git push *

## Запрос изменений с сервера

*git pull *
