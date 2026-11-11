# Banking

Банковский бизнес-модуль учебного проекта
[bank-learning-project](https://github.com/bank-learning-project).

Согласованный объём: клиенты, счета, внутренние переводы и выписки в рабочем
месте сотрудника. Модуль владеет доменом, прикладными сценариями, публичным Java API,
Vaadin-компонентами, отображением данных и миграциями Flyway.
Он также владеет процессом открытия счёта Camunda, отчётом BIRT и адаптерами Artemis.

## Границы

- Доменные классы не зависят от Vaadin, JDBC или ORM.
- Адаптер хранения использует собственную учебную библиотеку
  [orm](https://github.com/bank-learning-project/orm).
- Банковские правила, полномочия, инварианты денежных операций и границы их
  транзакций определяются в этом модуле.
- Сборка приложения, вход, конфигурация и жизненный цикл ресурсов принадлежат
  [app](https://github.com/bank-learning-project/app).

## Документация и обучение

- [Требования](https://github.com/bank-learning-project/app/blob/main/docs/requirements.md)
- [Архитектура](https://github.com/bank-learning-project/app/blob/main/docs/architecture.md)
- [Процесс разработки](https://github.com/bank-learning-project/app/blob/main/docs/development.md)
- [Учебные задачи и зависимости](https://github.com/bank-learning-project/app/blob/main/docs/learning-plan.md)

Сейчас опубликована документация; реализация ещё не начата. Код пишет разработчик
самостоятельно, помощник участвует в разборе и проверке. Используются только
синтетические данные. Канонические требования и план поддерживаются в `app`.
