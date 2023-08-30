# Содержимое сайта TMOEG

ПОДМОДУЛЬ репозитория https://github.com/tmoeg/tmoeg

Репозиторий отвечает за содержимое сайта.
В нем находятся Markdown файлы, css стили и ассеты, которые используются в [главном репозитории](https://github.com/tmoeg/tmoeg) для сборки статичных страниц с помощью движка [MkDocs.](https://www.mkdocs.org/)

Текущий технологический стек проекта сейчас "колхозный", и не обязательно окончательный. Мы открыты для предложений по его изменению.

Например, в целях упрощения кастомизация визуальной темы MKDocs реализована через [extra.css](https://squidfunk.github.io/mkdocs-material/customization/#additional-css) и инъекцию html тегов + js прямо в маркдаун статьи вместо стандартных средств шаблонизации или кастомной mkdocs темы.

Стили пока написаны на чистом css в одном файле без препроцессоров.

## Установка и использование

Клонируйте главный репозиторий https://github.com/tmoeg/tmoeg, чтобы протестировать статьи.

## Внесение вклада

Мы открытая платформа и приветствуем любой вклад в проект.
Вы можете:

- Сообщить об ошибках в Issues или улучшить, исправить, добавить статьи или целые разделы сайта
- Предложить изменение дизайна сайта
- Помочь с организацией, модерацией, предложить улучшения процесса совместной разработки

Разработка на начальных этапах, основные направления контента только определяются.
Процесс работы с контрибьюторами пока организован в ручном режиме.

Прежде чем создавать новый Issue или Pull Request, пожалуйста, убедитесь, что подобный Issue или Pull Request еще не создан или фича уже не находится в разработке.

Если вы не уверены, можете связаться с нами в Discord. Если не знаете, с чего начать, можете обратиться к следующим ресурсам:

- [Заходите в Discord, канал "сайт"](https://discord.gg/EBdzkaw7xa)
- [Список задач по контенту](https://github.com/orgs/tmoeg/projects/1/)
- [Список задач по верстке](https://github.com/orgs/tmoeg/projects/2/)

## Требования к Pull Request

>ОЧЕНЬ желательно, связываться с модераторами в Discord сообщества **ДО** начала работы над правками.

Присылайте свои PR в **"review"** ветку.

Вносимые вами изменения не должны противоречить лицензии CC BY-NC 4.0 (т.е. контент должен быть оригинальным или не иметь копирайта)

После доработки, обсуждения и проверки модерацией статьи попадают в published и билдятся.

## Лицензия

Распространяется по лицензии Creative Commons «Attribution-NonCommercial» 4.0 International License


