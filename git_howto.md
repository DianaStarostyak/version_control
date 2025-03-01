# Подсказка по Git

Создание репозитория:
```sh
git init
```
Получение информации от Git о текущем состоянии репозитория:
```sh
git status
```
Добавление файла к следующему коммиту:
```sh
git add
```
Создание коммита:
```sh
git commit -m "Message"
text
```
Вывод на экран истории всех коммитов с их хэш-кодами:
```sh
git log
```
Вывод на экран истории всех коммитов с хэш-кодами (сокращенный вариант):
```sh
git log --oneline
```
Переход от одного коммита к другому:
```sh
git checkout
```
Возвращение к актуальному состоянию и продолжение работы:
```sh
git checkout master
```
Разница между текущим файлом и закоммиченным файлом:
```sh
git diff
```
Перемещение по веткам:
```sh
git checkout <имя_ветки>
```
Отображение всех веток:
```sh
git branch
```
Cоздание новой ветки:
```sh
git branch <имя_ветки>
```
Объединение веток (сначала необходимо перейти на основную ветку):
```sh
git merge <имя_ветки>
```
Удаление ветки:
```sh
git branch -d <имя_ветки>
```
Визуализация всех веток, список всех комитов:
```sh
git log --graph
```
Клонирование внешнего репозиторияна локальный ПК:
```sh
git clone <url-адрес репозитория
```
Получение изменений и слияние с локальной версией:
```sh
git pull
```
Отправление локальной версии репозитория на внешний:
```sh
git push
```
Смена назания основной ветки:
```sh
git branch -M <новое_имя_ветки>
```
Показ заданного репозитория:
```sh
git remote show
```
Отправка всех изменений на удаленный репозиторий в ветку <имя_ветки>:
```sh
git push -u origin <имя_ветки>
```
Запрос подробной информации об удаленном репозитории:
```sh
git remote show origin
```
Удаление ветки в локальном репозитории:
```sh
git push origin --delete <имя_ветки>
```
Создание новой ветки и переключение на нее:
```sh
git checkout -b <имя_ветки>
```
