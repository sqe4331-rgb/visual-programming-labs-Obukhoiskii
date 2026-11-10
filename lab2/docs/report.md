\# Отчёт по лабораторной работе №2 (Node-RED)



\*\*ФИО:\*\* Обуховский Кирилл

\*\*Группа:\*\* УИР-241



\## Способ установки

Node-RED установлен через npm (без Docker).

\- Node.js: v26.13.0

\- Node-RED: v5.0.9



\## Освоенные ноды

В ходе работы я освоил следующие ноды: inject, debug, function, switch, change, template, http request, mqtt in/out, http in/response, ui\_gauge, ui\_chart, telegram receiver/sender/command, file in/out, flow context.



\## Использованные AI-промпты

1\. «Сгенерируй JS-код для function node с if/else, циклом for, массивом и объектом»

2\. «Составь Mustache-шаблон для JSON с полями name, lab, group»

3\. «Настрой MQTT flow с публичным брокером broker.hivemq.com»

4\. «Как в Node-RED настроить отправку сообщений в Telegram через бота»



\## Результаты работы (скриншоты)

Все скриншоты находятся в папке `screenshots`:

\- `00-node-npm-version.png` — версии Node.js и npm

\- `01-nodered-versions.png` — версия Node-RED

\- `01-inject-debug.png` — поток 2.1

\- `02-function.png` — поток 2.2

\- `03-switch.png` — поток 2.3

\- `04-change.png` — поток 2.4

\- `05-template.png` — поток 2.5

\- `06-http-request.png` — поток 2.6

\- `07-mqtt.png` — поток 2.7

\- `08a-endpoints-text.png`, `08b-endpoints-info.png`, `08c-endpoints-success.png`, `08d-endpoints-404.png` — поток 2.8

\- `09-dashboard.png` — поток 2.9

\- `10-telegram.png` — поток 2.10

\- `11-files.png` — поток 2.11

\- `12-context.png` — поток 2.12



\## Выводы

В ходе работы я освоил Node-RED как мощный low-code инструмент для визуального программирования. Я научился собирать потоки из готовых нод, писать логику на JavaScript в function-нодах, настраивать HTTP-эндпоинты и делать запросы к внешним API, работать с протоколом MQTT, Telegram-ботами и интерактивными дашбордами. Также я понял, как использовать контекст (flow context) для сохранения состояния и как работать с файловой системой на Windows.

