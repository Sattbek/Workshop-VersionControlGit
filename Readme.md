# Инструкция по работе с Git

## Что такое *Git*?
*Git* - одна из реализации рапределенных систем контроля версии позволяющая реализовать версионность, как локально так и на удаленном сервере. Сама популярная форма реализующая *Git*, - [GitHub](https://github.com/)

## Подготовка репозитория
Для создания в папке репозитория необходимо открыть эту папку в терминале и написать команду *git init*, после чего в этой папке создаться скрытая папка *.git*, таким образом папка станет репозиторием

## Создание "сохранений"

### Добавление файла к "сохранению"
ДЛя того чтобы добавить файл к сохранению нужно использовать команду *git add*. В терминале с открытой папкой-репозиторием нужно написать *git add <название файла>*, и этот файл добавиться к "сохранению". 

### Просмотр состояния репозитория 
Для просмотра состояния репозитория используется команда *git status*. В терминале с открытой папкой-репозиторием нужно написать команду *git status*. В результате можно увидеть следующие выводы:
1. On branch *** nothing to commit - это означает нет активных изменений
2. Intracked file - это означает, что имеются не отслеживаемые системной контроля версий
...


## Перемещение между "сохранениями"

## Журнал изменений 

## Ветки в git

## Слияние веток и решение конфликтов 

## Удаление веток