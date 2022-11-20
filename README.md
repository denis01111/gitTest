# Установка Git. Инструкция для всех-всех!
## Определение Git
Git - система контроля версий. Берёт на себя контроль версий проекта и позволяет переключаться между ними. ***Git хранит не файлы целиком, а отличия между ними.*** Это позволяет экономить память. Автор программы — Линус Торвальдс, создатель ОС Linux.


##  Полезные ссылки:

* [скачать Git bash](https://git-scm.com/download/win "переход на сайт git-scm")
* [установка Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview "ссылка на инструкцию по загрузке и настройке VSCode для разных типов ОС")
* [статья про Git на Хабре](https://habr.com/ru/post/541258/ "дополнительная документация") 

## Полезные команды
* **git --version** - возвращает версию Git, которая установлена в системе
* **git status** - показывате текущее состояние Git
* **git init** - создать репозиторий в текущем каталоге/запуск Git
* **git add** - добавляет содержимое рабочего каталога в индекс 
* **git commit** - фиксирует или сохраняет (после git add)
* **git log** -  увидеть количество сохранений
* **git checkout** - переключение между версиями
* **git diff** - показывает разницу между текущим файлом и сохраqнённым
* **git checkout master** - переключение между версиями.

*Нажатие клавиши ‘q’ возвращает в исходное окно терминала*

## Ветки в Git
* **git branch** - выводит список веток в репозитории
* **git branch new_branch_name** - создать новую ветку
* **git branch -d branch_to_delete** - удалить ветку
* **git checkout branch_name** - переход на ветку
* **git log –graph** - вывод коммитов в виде дерева
* **git merge branch_name** - сливает эту ветку с текущей

## Работа с удаленными репозиториями

* **git clone** - склонировать внешний репозиторий на наш ПК 
* **git pull - скачивает все из текущего репозитория и автомотически делает merge** с нашей версии
* **git push** - отправляет нашу версию репозитория на внешний репозиторий

## Pull request
* **Делаем fork репозитория**
* **Делаем clone СВОЕЙ версии репозитория**
* **Создаем новую ветку и в НЕЕ вносим свои изменения**
* **Фиксируем изменения (делаем коммиты)**
* **Отправляем свою версию в свой GitHub**
* **На сайте GitHub нажимаем кнопку pull request**
