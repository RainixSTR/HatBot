# HatBot

Телеграмм бот, который выдает совет о необходимости ношения шапки в данный момент времени

## Тесты

Main branch tests: [![tests pass status](https://github.com/RainixSTR/HatBot/actions/workflows/test_pipeline.yml/badge.svg?branch=main)](https://https://github.com/RainixSTR/HatBot/actions/workflows/test_pipeline.yml)

Develop branch tests: [![tests pass status](https://github.com/RainixSTR/HatBot/actions/workflows/test_pipeline.yml/badge.svg?branch=develop)](https://github.com/RainixSTR/HatBot/actions/workflows/test_pipeline.yml)

## Запуск проекта
- Для начала требуется склонировать репозиторий:

```git clone https://github.com/RainixSTR/HatBot.git```

Учитывая наличие Dockerfile, который упрощает запуск проекта, в инструкции будет рассмотрем способ запуска именно через него

0. Перед началом работы убедитесь в наличии установленного Docker-а через командную строку командой ```docker -v```
1. Из папки с проектом запустите командую строку
2. Далее необходимо создать образ с помощью команды ```docker build -t dockerfile .```
3. После создания образа его необходимо запустить, используя команду ```docker run dockerfile```
999. Вы - восхитительны!

## Взаимодействие с ботом
1. После запуска перейдите в Telegram и найдите там бота ```t.me/hat_damn_bot```
2. После ввода команды ```/start``` будет предложен список городов
3. Выберете необходимый город и получите совет, который, возможно, сбережет ваше здоровье!

## Пример работы
//Актуальная температура во время тестирования бота: в Москве - -7, Санкт-Петербурге - -3//

Ввод:

    Москва
    
Вывод:

    Думаю, сегодня точно стоит надеть шапку

Ввод:

    Питер
    
Вывод:

    Пока терпимо, но тут уже смотри сам

