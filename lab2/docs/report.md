# Отчёт по лабораторной работе №2 (Node-RED)

**ФИО:** Обуховский Кирилл
**Группа:** УИР-241

## Способ установки
Node-RED установлен через npm (без Docker).
- Node.js: v26.13.0
- Node-RED: v5.0.9

## Освоенные ноды
В ходе работы я освоил следующие ноды: inject, debug, function, switch, change, template, http request, mqtt in/out, http in/response, ui_gauge, ui_chart, telegram receiver/sender/command, file in/out, flow context.

## Использованные AI-промпты
1. «Сгенерируй JS-код для function node с if/else, циклом for, массивом и объектом»
2. «Составь Mustache-шаблон для JSON с полями name, lab, group»
3. «Настрой MQTT flow с публичным брокером broker.hivemq.com»
4. «Как в Node-RED настроить отправку сообщений в Telegram через бота»

## Результаты работы (скриншоты)

**Версии Node.js и Node-RED:**
![Версии](../screenshots/00-node-npm-version.png)
![Версия Node-RED](../screenshots/01-nodered-versions.png)

**Потоки 2.1 - 2.5:**
![2.1](../screenshots/01-inject-debug.png)
![2.2](../screenshots/02-function.png)
![2.3](../screenshots/03-switch.png)
![2.4](../screenshots/04-change.png)
![2.5](../screenshots/05-template.png)

**Потоки 2.6 - 2.10:**
![2.6](../screenshots/06-http-request.png)
![2.7](../screenshots/07-mqtt.png)
![2.8 text](../screenshots/08a-endpoints-text.png)
![2.8 info](../screenshots/08b-endpoints-info.png)
![2.8 success](../screenshots/08c-endpoints-success.png)
![2.8 404](../screenshots/08d-endpoints-404.png)
![2.9](../screenshots/09-dashboard.png)
![2.10](../screenshots/10-telegram.png)

**Потоки 2.11 - 2.12:**
![2.11](../screenshots/11-files.png)
![2.12](../screenshots/12-context.png)

## Выводы
В ходе работы я освоил Node-RED как мощный low-code инструмент для визуального программирования. Я научился собирать потоки из готовых нод, писать логику на JavaScript в function-нодах, настраивать HTTP-эндпоинты и делать запросы к внешним API, работать с протоколом MQTT, Telegram-ботами и интерактивными дашбордами. Также я понял, как использовать контекст (flow context) для сохранения состояния и как работать с файловой системой на Windows.
