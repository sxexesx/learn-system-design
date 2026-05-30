<div align="center">
  <img width="375" height="281" src="_src/sys-design.gif">
  <h3>Конспект по систем дизайну</h3>
</div>
В этом репозитории собраны основные теоретические вопросы необходимые для подготовки к интервью по систем-дизайну. А также примеры дизайна популярных решений. 

--- 

- [Виды информационных систем. Понятие архитектуры.](_notes/part_1.md)
    - [Что такое микросервисы?](_notes/part_1.md#что-такое-микросервис-плюсы-и-минусы-микросервисной-архитектуры)
    - [Уровни шаблонов микросервисной архитектуры](_notes/part_1.md#уровни-шаблонов-микросервисной-архитектуры)
    - [Понятие архитектуры](_notes/part_1.md#понятие-архитектуры)
    - [Принципы декомпозиции](_notes/part_1.md#принципы-декомпозиции)
    - [Принципы микросервисной архитектуры](_notes/part_1.md#принципы-микросервисной-архитектуры)

- [Распределенная система](_notes/part_2.md)
    - [Что это такое](_notes/part_2.md#что-это-такое)
    - [Свойства распределенной системы](_notes/part_2.md#основные-свойства-распределенных-систем)
    - [Установка требований к системе](_notes/part_2.md#требования-к-системе)
    - [Шаги по проектированию распределенных систем](_notes/part_2.md#шаги-по-проектированию-системы)
        

- [Балансировка нагрузки](_notes/part_3.md)
    - [Виды балансировки](_notes/part_3.md)
    - [Типы балансировки](_notes/part_3.md#типы-балансировки-нагрузки)
    - [Отказоустойчивость балансировки](_notes/part_3.md#отказоустойчивость)
    - [Проксирование](_notes/part_3.md#проксирование)
    
- [Кэширование](_notes/part_4.md)
    - [Что такое кэширование и какие проблемы оно решает](_notes/part_4.md)
    - [Как посчитать эффективность кэша](_notes/part_4.md#как-посчитать-эффективность-кэша)
    - [Виды кэширования](_notes/part_4.md#виды-кэширования)
    - [Способоы взаимодействия с кэшом](_notes/part_4.md#способы-взаимодействия-с-кэшом)
    - [Алгоритмы вытеснения данных](_notes/part_4.md#алгоритмы-вытеснения-данных)
    - [Алгоритмы кэширования](_notes/part_4.md#алгоритмы-кэширования)
    - [Инвалидация данных в кэше](_notes/part_4.md#инвалидация-данных-в-кэше)
    - [Многомерный кэш](_notes/part_4.md#многомерный-кэш)

- [API](_notes/part_5.md)
    - [Подходы HTTP](_notes/part_5.md#подходы-http)
    - [Проблемы проектирования](_notes/part_5#проблемы-проектирования)
    
- [Observability](_notes/part_6.md)
    - [Мониторинг](_notes/part_6.md#мониторинг)
    - [Алертинг](_notes/part_6.md#алертинг)
    - [Логирование](_notes/part_6.md#логирование)
    - [Непрерывное профилирование](_notes/part_6.md#непрерывное-профилирование)
    - [SLO, SLI, SLA](_notes/part_6.md#sla-slo-sli)
    - [DORA-метрики](_notes/part_6.md#sla-slo-sli)

- [Базы данных](_notes/part_7.md)
    - [Виды баз данных](_notes/part_7.md#виды-баз-данных)
    - [Выбор баз данных](_notes/part_7.md#как-выбирать-базы-данных)
    - [OLAP vs OLTP](_notes/part_7.md#olap-vs-oltp)
    - [Где хранятся данные баз данных](_notes/part_7.md#где-хранятся-данные-в-бд)
    - [Индексы](_notes/part_7.md#индексы)
    - [ACID](_notes/part_7.md#acid)
    - [BASE](_notes/part_7.md#base)
    - [Аномалии транзакций](_notes/part_7.md#аномалии-транзакций)
    - [Решение проблем изоляции](_notes/part_7.md#решение-проблем-изоляции)

- [Брокеры сообщений](_notes/part_8.md#брокер-сообщений)
    - [Почему kafka?](_notes/part_8.md#почему-kafka)
    - [Топики и партиции](_notes/part_8.md#топики-и-партиции)
    - [Консьюмер группа](_notes/part_8.md#консьюмер-группа)
    - [Гарантирован ли порядок сообщений в кафке?](_notes/part_8.md#гарантирован-ли-порядок-сообщений-в-кафке)
    - [Гарантии доставки](_notes/part_8.md#гарантии-доставки)

- [Паттерны хранения данных](_notes/part_9.md#паттерны-хранения-и-доставки-данных)

- [Расчет ресурсов для системы](_notes/part_9.md#расчет-ресурсов-для-системы)

- [Хранение данных распределенно](_notes/part_10.md)
    - [Бэкапы](_notes/part_10.md#бэкап)
    - [Реликация](_notes/part_10.md#репликация)
    - [Виды репликаций](_notes/part_10.md#виды-репликации)
    - [CAP теорема](_notes/part_10.md#cap-теорема)
    - [Партиционирование](_notes/part_10.md#партиционирование)
    - [Шардирование](_notes/part_10.md#шардирование)
    - [Роутинг данных](_notes/part_10.md#routing-данных)
    - [Альтернативный способ хранения данных](_notes/part_10.md#альтернативные-способы-хранения-данных)

- [Ограничитель трафика](_notes/part_11.md)
    - [Алгоритм маркерной корзины](_notes/part_11.md#алгоритм-маркерной-корзины-token-bucket)
    - [Алгоритм дырявого дерева](_notes/part_11.md#алгоритм-дырявого-ведра-leaking-bucket)
    - [Счетчик фиксированных интервалов](_notes/part_11.md#счетчик-фиксированных-интервалов-fixed-window-counter)
    - [Журнал скользищих интервалов](_notes/part_11.md#журнал-скользящих-интервалов-sliding-window-log)
    - [Счетчик скользящих интервалов](_notes/part_11.md#счетчик-скользящих-интервалов-sliding-window-counter)

- [Архитектура ИС](_notes/part_12.md#архитектуры-ис)
- [Синхронная и асинхронные коммуникации](_notes/part_12.md#коммуникации)
    - [Цепочка](_notes/part_12.md#синхронные-цепочка)
    - [Агрегатор](_notes/part_12.md#синхронные-агрегатор-api-composition)
    - [Put/take](_notes/part_12.md#асинхронные-точка-точка-puttake)
    - [Pub/sub](_notes/part_12.md#асинхронные-издатель-подписчик-pubsub)
    - [Две очереди ](_notes/part_12.md#асинхронные-две-очереди-requestresponse)
- [Event sourcing](_notes/part_12.md#event-sourcing)

- [Виды релизов](_notes/part_13.md#виды-релизов)

- [Подходы в проектировании](_notes/part_13.md)
    - [Ретраи](_notes/part_13.md#ретраи)
    - [Идемпотентность](_notes/part_13.md#идемпотентность)
    - [Backoff](_notes/part_13.md#backoff)
    - [Rate limiting](_notes/part_13.md#rate-limiting)
    - [Load shedding](_notes/part_13.md#load-shedding)
    - [Backpressure](_notes/part_13.md#backpressure)
    - [Circuit Breaker](_notes/part_13.md#circuit-breaker)
    - [Self-healing](_notes/part_13.md#self-healing)
    - [Graceful degradation](_notes/part_13.md#graceful-degradation)
    - [Fallback](_notes/part_13.md#fallback)
    - [Failover caching](_notes/part_13.md#failover-caching)
    - [Dead letter queue](_notes/part_13.md#dead-letter-queue)
    - [API Gateway](_notes/part_13.md#api-gateway)
    - [Throttling/Debouncing](_notes/part_13.md#throttling--debouncing)
    - [CQRS (Command and Query Responsibility Segregation)](_notes/part_13.md#cqrs-command-and-query-responsibility-segregation)

- [Консенсус](_notes/part_14.md)
    - [Распределенные транзакции. 2PC](_notes/part_14.md#two-phase-comnit-2pc)
    - [Распределенные транзакции. SAGA](_notes/part_14.md#saga)
    - [Transactional Outbox](_notes/part_14.md#transactional-outbox)
    - [Transactional Inbox](_notes/part_14.md#transactional-inbox)
    - [Как распространять изменения между узлами?](_notes/part_14.md#как-распространять-изменения-между-узлами)
    - [Модели согласованности](_notes/part_14.md#модели-согласованности)


---

- Практика
    - [Практика установки требований и оценки нагрузки](_notes/practice_1.md)
    - [Система апдейтов операционной системы мобильного устройства](_notes/practice_3.md)
    - [Статус пользователя](_notes/practice_4.md)
    - [Система нотификаций](_notes/practice_5.md)
    - [Мэссенджер](_notes/practice_6.md)

