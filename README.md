[![Build Status](https://travis-ci.org/sima-land/api-v5-php-client.svg?branch=master)](https://travis-ci.org/sima-land/api-v5-php-client)
[![StyleCI](https://styleci.io/repos/121488685/shield)](https://styleci.io/repos/121488685)
[![Code Coverage](https://scrutinizer-ci.com/g/sima-land/api-v5-php-client/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/sima-land/api-v5-php-client/?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/sima-land/api-v5-php-client/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/sima-land/api-v5-php-client/?branch=master)

# Библиотека для работы с API v5 www.sima-land.ru

Библиотека для получения каталога интернет-магазина [www.sima-land.ru](https://www.sima-land.ru/api/v5/help).
Предназначена для разработчиков которые хотят максимально быстро
подключить каталог [www.sima-land.ru](https://www.sima-land.ru/api/v5/help) к себе на сайт и 
не является готовым решением которое можно самостоятельно, без привлечения программиста, 
подключить к интернет магазину.

Версия библиотеки совпадает с версией API которую она использует. В настоящий момент
актуальной версией API является [API v5](https://www.sima-land.ru/api/v5/help)

Библиотека состоит из двух основных компонентов клиента и парсера:

- клиент позволяет делать произвольные запросы к API sima-land.ru, формирует все необходимые для этого заголовки.
- парсер использует клиент и позволяет загрузить данные и сохранить их в указанное место.

## Содержание

- [Установка и требования](doc/requirements.md)
- [Клиент](doc/client.md)
- [Парсер](doc/parser.md)
- [Примеры](doc/example.md)
- [Логирование](doc/logger.md)
- [FAQ](doc/FAQ.md)

## Документация API

* [https://www.sima-land.ru/api/v5/help](https://www.sima-land.ru/api/v5/help)

## Ограничение

- Не более 30 запросов в секунду
- Не более 5 запросов с ошибками секунду

## Тесты

Тесты запускаются из корневой директории пакета.

```sh
php ./vendor/bin/phpunit
```

## Если что-то пошло не так

Вы можете задать вопрос в [issue](https://github.com/sima-land/api-v5-php-client/issues)

