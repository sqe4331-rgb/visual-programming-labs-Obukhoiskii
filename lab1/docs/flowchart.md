```mermaid
flowchart TD
    Start([Начало]) --> A[Получить данные]
    A --> B{Данные полные?}
    B -- Нет --> C[Запросить данные]
    C --> End([Конец])
    B -- Да --> D[Одобрить заявку]
    D --> End
```Fix flowchart spaces
