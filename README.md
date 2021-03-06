
# [OTUS.ru - Data Engineer - Инженер Данных](https://otus.ru/lessons/data-engineer/)

## [Модуль 1. «Инженер Данных: задачи, инструменты, платформы».](./module-1/)
---

### Занятие 1. Инженер Данных. Задачи, навыки, инструменты, потребности на рынке.

*   Data Engineer: потребность и ценность
*   Задачи, навыки, инструменты, классификации данных
*   Создание ценности и вызовы

#### [Домашнeе заданиe № 1. Анализ рынка Инженер Данных: РФ, USA, EU.](/module-1/hw-1-de/)

### Занятие 2. Эволюция подходов работы с данными. Базовые принципы и понятия.

*   История и эволюция подходов работы с данными
*   Технологические основы аналитических решений
*   CAP theorem, Distributed Computing, MPP (Massive Parallel Processing)
*   SQL + Not Only SQL
*   Подходы к обработке данных: Batch & Stream
*   Архитектуры: Lambda, Kappa

### Занятие 3. Платформы для обработки данных

*   Облака vs On-premises: возможности, преимущества, особенности
*   Экосистема Hadoop и элементы Системы Обработки Данных
*   Обзор инструментов Cloudera, Hortonworks, GCP, AWS


#### [Домашнeе заданиe № 2. Развернуть дистрибутив Cloudera](/module-1/hw-2-cloudera/)

### Занятие 4. Форматы хранения данных и их особенности.

*   Обзор популярных форматов: CSV, JSON, Avro, Parquet, ORC
*   Анализ применения и производительности форматов
*   Бинарные и человеко-читаемые форматы хранения
*   Schema evolution, Compression, Bloom filters, Indexing


## [Модуль 2. Фреймворк для распределенных вычислений Apache Spark](/module-2/)
---

### Занятие 5. Введение в Scala.

*   Синтаксис и простые выражения в Scala
*   Управляющие конструкции: if, for, pattern matching
*   ООП: Class, Object, Trait
*   Implicits
*   Инструменты для разработки: sbt, IntelliJ IDEA

### Занятие 6. Apache Spark - 1 часть.

- Spark - что это и зачем он нужен
- API - RDD, Dataset, Dataframe, операции над распределенными коллекциями
- Процесс вычисления в Spark - task, stage, оптимизатор запросов

### Занятие 7. Apache Spark - 2 часть.

- Spark - что это и зачем он нужен
- API - RDD, Dataset, Dataframe, операции над распределенными коллекциями
- Процесс вычисления в Spark - task, stage, оптимизатор запросов

#### [Домашнeе заданиe № 3. Введение в Spark + Гид по безопасному Бостону](/module-2/hw-3-spark/)

### Занятие 8. Jupyter Notebook. Интерактивная аналитика и визуализация.

- Инструменты интерактивной аналитики
- Google Cloud Datalab
- Jupyter - интеграция с Apache Spark

### Занятие 9. Spark Streaming.

- Micro-batch обработка данных
- Классический Spark Streaming
- Structured Streaming
- Continuous processing

### Занятие 10. Очереди сообщений, Kafka, Confluent platform.

- Kafka, RabbitMQ
- Потоковая обработка (виды обработки, описание Producer–consumer problem, пример архитектурного решения через Kafka, RabbitMQ, NATS)
- Google Dataflow paper (Event time vs processing time и так далее).
- Паттерны stream processing Joins, enricher, router. Event-sourcing.


## [Модуль 3. «Загрузка данных (Data Ingestion) и обучение моделей ML».](./module-3/)
---

### Занятие 11. Распределенные файловые системы.

- Принципы работы распределенных файловых систем
- Структура кластера HDFS
- Тонкости настройки HDFS - конфигурация, защита, обеспечение отказоустойчивости

### Занятие 12. Инструменты выгрузки данных из сторонних систем.

- Типы систем-источников. Структурированные, полу- и неструктурированные данные. Логи, выгрузки из АС, Clickstream
- Инструменты для извлечения и загрузки данных - Flume, Sqoop, StreamSets, Fluentd, Debezium, logstash
- Практические примеры загрузки данных из сервисных баз данных

### Занятие 13. Обучение моделей. ML.

- Пример построения модели

### Занятие 14. ML модели в Production.

- Использование Flask приложение и REST API для создания сервиса ML
- Применение Docker контейнеров для развертывания ML код

#### [Домашнeе заданиe № 4. Обучение и вывод модели ML.](module-3/hw-4-ml/)

## [Модуль 4. «Хранилища данных. SQL-доступ к данным».](./module-4/)
---

### Занятие 15. DWH. Семейство MPP баз - назначение и особенности.

- Семейство MPP баз - назначение и особенности
- Логический и физический дизайн
- Vertica

### Занятие 16. DWH. Моделирование Хранилища данных.

- Семейство MPP баз - назначение и особенности
- Логический и физический дизайн
- Google BigQuery

#### [Домашнeе заданиe № 5. Проектирование DWH и витрины данных.](module-4/hw-5-dwh/)

### Занятие 17. Хранилища NoSQL. Назначение и особенности.

- NoSQL Databases. HBase, Cassandra, Elasticsearch, Aerospike
- Key-value
- Cache

### Занятие 18. SQL-доступ к данным. Apache Hive.

- SQL - межгалактический язык работы с данными

#### [Домашнeе заданиe № 6. HiveQL.](module-4/hw-6-hive/)

### Занятие 19. ElasticSearch.

- Знакомство с компонентами ELK-стэка
- Классы задач, для которых подходит ELK

## [Модуль 5. «Обеспечивающие системы. Оркестрация, тестирование, мониторинг».](./module-5/)
---

### Занятие 20. Оркестрация.

- Как организовать многоэтапные процессы обработки данных
- Инструменты оркестрации - Oozie, Airflow

### Занятие 21. Практики DevOps: CI/CD в ML.

- Культура DevOps
- Интеграция, тестирование, развертывание

### Занятие 22. Мониторинг.

- Инструменты мониторинга - Prometheus, Zabbix, Graphite, Grafana
- Специфика мониторинга процессов обработки данных

### Занятие 23. Data Quality. Контроль качества данных, автотесты, мастер-данные.

- Data Quality and Consistency. Качество данных. MDM
- Ошибки в коде, логике, виды, последствия, как найти и устранить корневую причину
- Вопросы поддержки. Support
- Метрики качества. Контроль качества. Data Fix - как исправлять найденные ошибки
- MDM: управление мастер-данными

### Занятие 24. Case studies. Кейсы компаний.

- Углубленные вопросы оптимизации. Фишки. Примеры, разбор

### Занятие 25. Дальнейшее развитие навыков и полезные ресурсы.

- Где искать ответы на вопросы. Ресурсы. Как быстро разбираться и решать проблемы.
- Benchmarking - умеем сравнивать инструменты для решения конкретных задач
- Как грамотно составить резюме (CV) + proof-read резюме участников курса
- Как развиваться в плане Soft skills, Hard skills. Contribution.

## [Модуль 6. «Проектная работа».](./module-6/)
---

Выпускной проект: реализация задачи по выбранной тематике в реальном времени с применением парадигмы Map-Reduce кластере в виде pipeline (Kafka, Spark, Hadoop экосистема) и визуализация результатов.

Список возможных тем проектов будет предложен. Также можно взять задачу "с работы" или близкого себе проекта.

Проектная работа «Проектная работа».

### Занятие 26. Вводное занятие по проектной работе.

Слушатели курса смогут определиться с темой проекта (выбрать из предложенного списка или привнести задачу из деятельности своей компании), получить понимание какие ресурсы им необходимо использовать для работы.

#### [Домашнeе заданиe № 7. Проектная работа.](/module-6/hw-7-project/)

### Занятие 27. Консультация по проектной работе.

Слушатели курса получат комментарии относительно прогресса проектной работы, ответы на вопросы, рекомендации по реализации.

### Занятие 28. Защита проектной работы.

По окончании занятия слушатели курса получат разбор проектов, комментарии и оценку своей работы.
