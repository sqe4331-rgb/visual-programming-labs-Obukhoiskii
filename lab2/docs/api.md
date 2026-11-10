\# API Documentation

\## GET /api/text

Ответ: `Это простой текстовый ответ от Node-RED.`

\## GET /api/info

Ответ: `{"status":"ok","author":"Обуховский Кирилл","group":"УИР-241"}`

\## GET /api/items/:id

\- Успех (/api/items/1): `{"id":1,"name":"Item One","author":"Обуховский"}`

\- Ошибка (/api/items/999): 404 `{"error":"Not found","id":"999"}`

