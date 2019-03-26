
[![Stars](https://img.shields.io/github/stars/khorevaa/files.svg?label=Github%20%E2%98%85&a)](https://github.com/khorevaa/files/stargazers)
[![Release](https://img.shields.io/github/tag/khorevaa/files.svg?label=Last%20release&a)](https://github.com/khorevaa/files/releases)
[![Открытый чат проекта https://gitter.im/EvilBeaver/oscript-library](https://badges.gitter.im/khorevaa/files.png)](https://gitter.im/EvilBeaver/oscript-library)

[![Build Status](https://travis-ci.org/khorevaa/files.svg?branch=master)](https://travis-ci.org/khorevaa/files)
[![Coverage Status](https://coveralls.io/repos/github/khorevaa/files/badge.svg?branch=master)](https://coveralls.io/github/khorevaa/files?branch=master)

# Библиотека files

    > Облегает чтение и запись текста в файлы, и сериализацию в/из json

## Возможности

Реализован класс `Файлы`
Методы класса:
* `ПрочитатьФайл` - Выполняет чтение текста файла и возвращает полученную строку
* `ЗаписатьФайл` - Выполняет запись текста в файл
* `ОБъектВJson` - Выполняет преобразование объекта в текста json
* `ОбъектИзJson` - Выполняет преобразование из текста json в объект

Реализован модуль `РаботаСФайлами` - методы аналогичные классу `Файлы`

## Установка

Для установки необходимо:
* Скачать файл files.ospx из раздела [releases](https://github.com/khorevaa/files/releases)
* Воспользоваться командой:

```
opm install -f <ПутьКФайлу>
```
или установить с хаба пакетов

```
opm install files
```

## Публичный интерфейс

[Документация публичного интерфейса (в разработке)](docs/README.md)

## Доработка

Доработка проводится по git-flow. Жду ваших PR.

## Лицензия

Смотри файл [`LICENSE`](LICENSE).
