# Test Markdown

## Списки

### Неупорядочные списки

Проверка абзац текста
* Список1

* Список2
* Список3

### Упорядоченные списки

1. Список1
2. Список2
3. Список3

## Горизонтальные линии разделители

## Выделение текста

Markdown воспринимает звёздочки «*» и символы подчёркивания «_» как признаки смыслового выделения текста:
<<<<<<< HEAD
Иными словами, текст, окруженный одинарными символами, выделяется курсивным шрифтом, а текст, окруженный двойными символами, выделяется полужирным шрифтом. Также, выделенный фрагмент может находиться в любой части слова. 

=======

Текст, окружённый одиночными «*» или «_», будет заключен в HTML-тэг <em>.
Текст, окружённый двойными «*» или «_», будет заключен в HTML-тэг <strong>.

## Кодовые фрагменты

Чтобы отметить фрагмент строки, содержащий код, необходимо окружить его обратными апострофами «`». При использовании кодовых фрагментов строк текст будет отображаться в виде моноширинного шрифта. В отличие от блоков кода, кодовый фрагмент позволяет поместить код внутрь обычного абзаца текста.

# Работа с удаленными репозиториями

## Инструкция по созданию pull request

1. Необходимо сделать forked (ответвление) полную копию интересующего репозитория на своем аккаунте для дальнейшей работы с ним.
2. Находясь на своем аккаунте коппируем ссылку для клонирования в локальную папку.
3. Выбираем в локальной версии Git нужную папку и клонируем в нее скопированный репозиторий (команда clone)
4. Проваливаемся внутрь данного репозитория (команда cd)
5. Создаем отдельную ветку с предлагаемыми изменениями (команда git branch) и производим все изменения только в ней.
6. Отправляем эти изменения на свой аккаунт в удаленный репозиторий(команда push)
7. Переходим на свой аккаунт GitHub. В открывшемся окне выбираем функцию pull request.
