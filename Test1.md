# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
**Git** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

*Git add*
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

## Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение), необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

# Ветки в Git

## Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Добавление картинок

Для того, чтобы добавить **картинку**, надо:
![Картинка](https://avatars.mds.yandex.net/i?id=ec3ec0d07be522761e8f24e28b2ba213277ce725-8208034-images-thumbs&n=13)

![Новая картинка](https://avatars.mds.yandex.net/i?id=a8bfec79b6b2aade18d228a9dd5bc00b0bfaa6c1-7178390-images-thumbs&n=13)

## Добавление ссылок

Для того, чтобы добавить ***ссылку***, надо:
[Инструкция](https://habr.com/ru/company/ruvds/blog/501648/)

Добавила ссылку на программу Git:
[Скачать Git](https://git-scm.com/downloads)


## Добавление списков и цитат
* Ненумерованные списки задаются тремя фигурами:
* Первый
+ Второй
- Третий

Чтобы добавить *цитату*, используем знак ">"
>Текст цитаты

Чтобы добавить *цитату в цитате*, надо:
>Текст первой цитаты
>>Текст второй цитаты
>>>Текст третьей цитаты и т.д. до 15

>Кто думает как победитель, рано или поздно побеждает. Ричард Бах

>> Любить — значит видеть человека таким, каким его задумал Бог. (Ф.М. Достоевский)

