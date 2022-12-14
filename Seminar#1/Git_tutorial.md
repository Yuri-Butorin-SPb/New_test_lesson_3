# Туториал по GIT
![Logo](pic.jpeg)
Это будет наш маленький справочник по системе контроля версий.

## Инициализация репозитория

Чтобы инициализировать репозиторий (создать место для изменения версий файлов), используйте следующую команду:

```
git init
```
## Добавление файлов в репозиторий

Чтобы добавить файл в репозиторий, необходимо прописать следующую команду:

```
git add <название файла>
```

## Получение информации о текущем состоянии

ЧТобы получить информацию от git о его текущем состоянии, используйте следующую команду

```
git status
```

## Создание коммита

Чтобы создать коммит, воспользуйтесь командой

```
git commit -m "message"
```
### Примеры имен коммитов
* init: - используется для начала проекта/таска.
* feat: - это реализованная новая функциональность из технического задания (добавил поддержку зумирования, добавил footer, добавил карточку продукта).
* fix: - исправил ошибку в ранее реализованной функциональности.
refactor: - новой функциональности не добавлял / поведения не менял. Файлы в другие места положил, удалил, добавил. Изменил форматирование кода (white-space, formatting, missing semi-colons, etc). Улучшил алгоритм, без изменения функциональности.
* docs: - используется при работе с документацией/readme проекта.

## История всех коммитов
Для вывода на экран истории всех коммитов с их хэш-кодами, нужно воспользоваться командой

```
 git log
```

### Пример:

```
commit c2ab8b9d8baf7283da63b9d1f8a55970954e6763 (HEAD -> master)
Author: Yuri <butor.yuri@gmail.com>
Date:   Sun Nov 20 19:16:21 2022 +0300

    docs:update file tutorial, add fourth command
```

## Переход по коммитам
Для перехода от одного коммита к другому, воспользуйтесь командой

```
git checkout
```
Для возврата к **актуальному** состоянию и для продолжения работы, наберите:

```
git checkout master
```

## Разница между _текущим_ файлом и _закоммиченным_

```
git diff
```


