# AIRA-email-templates
Here it is markup for e-mail templates for projects aira.life and robonomics.network
## Общая информация о шаблонах
* `template-email-` основной шаблон письма
* `system-email-` системные письма (например, используемые в работе сайта)
* `event-email-` письма, посвященные какому-либо конкретному событию, отличающиеся от писем стандартного назначения
* `event-webemail-` веб версия письма, посвященного конкретному событию. Основное отличие на сегодня от *event-email-* это пути ко временным файлам
* `old-` старые версии шаблонов, их не нужно использовать
Во всех файлах далее после черточки идёт более конкретное назначение шаблона.
## Информация о работе с путями изображений в шаблоне
* В шаблонах есть 2 типа изображений: постоянные и временные.
* Исходники постоянных файлов лежат в директории `files/`
* Постоянные файлы загружаются владельцем репозитория на отдельный поддомен и если вы берете шаблон в качестве основы для верстки текущего стандартного письма, вам не нужно о них задумываться
* Исходники временных файлов лежат в директории `files/tmp`
* Временные файлы меняются от письма к письму, определяются и загружаются специалистом, верстающим текущую версию письма
* Временные файлы загружаются на сервер сервиса почтовых рассылок при загрузке шаблона
* Исключение для путей временных файлов: если верстается web-версия письма (зачастую для поддержки мультиязычности), то файлы загружаются владельцем репозитория на отдельный поддомен.
## Где тестировались актуальные шаблоны

Актуальными считаются шаблоны со следующими именами: `template-email-`, `system-email-`. Актуальность всех остальных шаблонов при желании использовать необходимо уточнять.

Итак, где тестировались актуальные шаблоны: Mail.ru, Google.com (web версия и мобильный клиент), Yandex.ru, Apple Почта Версия 11.3

О любых ошибках в коде сообщайте владельцу репозитория лично или в Issues репо.
## Другие ссылки
[Рекомендации по загрузке сверстанных писем в Unisender](https://docs.google.com/document/d/15cmNt5l1WRy2l_7bVpt-Hmtgv6uCu33Dzx49S82w69g) – приватный Google-документ, нужно запросить доступ и указать в комментарии обоснование
