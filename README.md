# GA-sequences-transactions
## Формирование цепочки из источников визитов, которые привели к транзакции

#### 1) Получил доступ к данным внутри BigQuery
#### 2) Выгрузил данные за 1 календарный месяц
  - Определил поля данных
  - Составил SQL запрос
  - Подключился по API к BigQuery
  - Выгрузил датасет
#### 3) Сформировал последовательность источников визитов пользователя, которые привели к транзакции
  - Определил источник как связку utm_source + utm_medium
  - Отфильтровал транзакционные визиты
  - Для каждой транзакции сформировал цепочку касаний
  - Вывел Топ-10 самых популярных цепочек касаний за выбранный период
