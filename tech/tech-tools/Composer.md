# Composer

Использую Composer с ~2014 года. С тех пор это основной инструмент для управления зависимостями во всех PHP-проектах - и рабочих, и личных.


## Опыт использования

### Базовые операции

Уверенно работаю со всеми основными командами: установка и обновление пакетов, управление версиями, автозагрузка классов, работа с scripts. Composer стал неотъемлемой частью рабочего процесса - нет смысла отказываться от удобного инструмента.


### Создание собственных пакетов

Создал несколько composer-пакетов для переиспользования кода между проектами:

- **[Php_Client](../../experience/projects/Php_Client.md)** - серия API-клиентов для различных сервисов:
  - [php-client/openai](https://github.com/php-client/openai) - клиент для OpenAI API
  - [php-client/ollama](https://github.com/php-client/ollama) - клиент для Ollama
  - [php-client/tailscale](https://github.com/php-client/tailscale) - клиент для Tailscale VPN
  - [php-client/keenetic](https://github.com/php-client/keenetic) - клиент для роутеров Keenetic
  - [php-client/syncthing](https://github.com/php-client/syncthing) - клиент для Syncthing
  - [php-client/support](https://github.com/php-client/support) - общая библиотека для клиентов

- **[Vk_Client](../../experience/projects/Vk_Client.md)** - PHP-клиент для работы с VK API:
  - [laravelrus/vk-client](https://github.com/laravelrus/vk-client) - клиент для VK API

- **[Laravel_Vk_Requester](../../experience/projects/Laravel_Vk_Requester.md)** - Laravel-пакет для автоматизации работы с VK API:
  - [laravelrus/laravel-vk-requester](https://github.com/laravelrus/laravel-vk-requester) - (архивный)

- **[Inboxly](../../experience/projects/Inboxly.md)** - агрегатор RSS/Atom фидов:
  - [inboxly/receiver](https://github.com/inboxly/receiver) - библиотека для парсинга RSS и Atom фидов

- **[Content_Store](../../experience/projects/Content_Store.md)** - сервис для сохранения контента:
  - content-fetcher - пакет для получения и конвертации контента

- **[Laravel_Stubs](../../experience/projects/Laravel_Stubs.md)** - пакет для настройки stub-файлов Laravel:
  - [laravelrus/laravel-stubs](https://github.com/laravelrus/laravel-stubs) - (архивный, функционал добавлен во фреймворк)

- **[PhpIL](../../experience/projects/PhpIL.md)** - библиотека для работы с изображениями:
  - [phpil/phpil](https://github.com/phpil/phpil) - (не завершен, только наброски)

- **[Micro-framework_La](../../experience/projects/Micro-framework_La.md)** - экспериментальный микро-фреймворк:
  - La - минимальное ядро фреймворка (удален)
  - Lapp - каркас базового приложения (удален)

Все пакеты публиковал на Packagist для удобства установки через `composer require`.


### Локальная разработка пакетов

Часто использую возможность Composer подгружать пакеты локально из директорий рядом с проектом через `path` repositories. Это удобно для разработки и тестирования пакетов до их публикации.

С приватными репозиториями (Packagist Private, Satis) не работал - всегда хватало либо публичных пакетов, либо локальной загрузки.


## Примеры применения

### В рабочих проектах

- **[2021-2024_-_Morizo](../../experience/work/dev/2021-2024_-_Morizo.md)** - управление зависимостями
- **[2018-2019_-_BTrud](../../experience/work/dev/2018-2019_-_BTrud.md)** - управление зависимостями
- **[2016-2017_-_Appwilio](../../experience/work/dev/2016-2017_-_Appwilio.md)** - управление зависимостями
- **[2016-2016_-_DSE](../../experience/work/dev/2016-2016_-_DSE.md)** - управление зависимостями
- **[2015-2016_-_TRM](../../experience/work/dev/2015-2016_-_TRM.md)** - управление зависимостями


### В других личных проектах

- **[Inboxly](../../experience/projects/Inboxly.md)** - агрегатор RSS/Atom фидов
- **[CMF](../../experience/projects/CMF.md)** - экспериментальный Content Management Framework
- **[Content_Store](../../experience/projects/Content_Store.md)** - сервис для сохранения контента
- **[UniParser](../../experience/projects/UniParser.md)** - веб-приложение для разработки парсеров
- **[WantUs](../../experience/projects/WantUs.md)** - сервис мониторинга сообщений в VK

Да и практически во всех остальных PHP-проектах с 2014 года использовал Composer как стандартный инструмент для управления зависимостями и автозагрузки классов.
