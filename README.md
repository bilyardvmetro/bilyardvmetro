# О себе

Меня зовут Кирилл. Мне 21 год. Обучаюсь на 4 курсе в Университете ИТМО.

Занимаюсь разработкой на Go и Java 4-й год. Программированием занимаюсь с 2020 года

Здесь собраны мои основные проекты и учебные репозитории. Проекты расположены отсортированы по дате по убыванию (сначала самые новые)

## Pet проекты на Java

- [Spring Boot REST Сервис сокращения ссылок с Kafka и мониторингом](https://github.com/bilyardvmetro/URLShortener)

> Spring Boot, PostgreSQL, Flyway, Kafka, Prometheus, Grafana, Docker, Gradle
  
Приложение позволяет создавать короткие ссылки для заданного URL и собирать статистику переходов. При каждом переходе по короткой ссылке сервис выполняет редирект на оригинальный URL и отправляет событие в Kafka, далее отдельный consumer сохраняет информацию о клике в PostgreSQL.

- [CRUD-приложение на Spring Boot с инфраструктурой мониторинга](https://github.com/bilyardvmetro/spring-crud)

> Spring Boot, PostgreSQL, Maven, Zabbix, Graylog, Prometheus, Grafana, Docker

Приложение позволяет исполнять CRUD операций над пользователями, проектами и задачами. Пользователь участвует в одном и более проектов, в проекте есть одна и более задач

- [IS-Lab1](https://github.com/bilyardvmetro/IS-Lab1)

>

blank

- [REST приложение на JAX-RS](https://github.com/bilyardvmetro/OPI-Lab4)

> Jakarta EE (JAX-RS), Hibernate, PostgreSQL, Gradle, Grafana, Prometheus, JWT

Приложение позволяет кликать на точки по области и собирать по ним статистику. В проекте есть gradle джобы, prometheus и grafana для сбора и визуализации метрик

- [Клиент-Серверное десктоп приложение на Java](https://github.com/bilyardvmetro/ITMO-System-Application-Software/tree/main/1%20%D0%BA%D1%83%D1%80%D1%81/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/2%20sem/Lab8)
> Java, JavaFX, PostgreSQL, Maven

Приложение позволяет исполнять CRUD операций над объектами, а также отображает их в GUI. Приложение поддерживает одновременную работу нескольких клиентов

## Pet проекты на Go

- [Экосистема для инвестиций. Сервис-агрегатор котировок](https://github.com/awesoma31/TrumpInvestitions)

> Go, REST API, Clickhouse, Docker, Git, Clickhouse, Postman, OpenAPI

Проект представляет из себя упрощенную экосистему для инвестиций. Приложение имеет нативный Android клиент и кроссплатформенное мобильное клиентское приложение. Пользователи выставляют заявки на покупку/продажу акций. Система при помощи автопокупки исполняет заявки. Пользователи имеют доступ к аналитике по портфелю. Проект разрабатывался в команде из 8 человек.

- [GraphQL сервис постов и комментариев](https://github.com/bilyardvmetro/ozon-Posts-And-Comments-test-project)

> Go, GraphQL, gqlgen, PostgreSQL, Docker, Github CI

Проект позволяет создавать и получать посты, создавать и получать комментарии к ним. Комментарии поддерживают любой уровень вложенности, комментарии к посту можно закрыть/открыть (тогглить), а также можно подписаться на получение комментариев к посту.

- [REST Pull Request сервис](https://github.com/bilyardvmetro/avito-PR-project)

> Go, REST API, PostgreSQL, Docker, Github CI, OpenAPI

Сервис автоматически назначает ревьюеров на Pull Request’ы (PR), а также позволяет управлять командами и участниками. Сервис назначает ревьюеров на PR из команды автора, позволяет выполнять переназначение ревьюверов и получать список PR’ов, назначенных конкретному пользователю, а также управлять командами и активностью пользователей. 


- [ASM язык с эмулятором процессора RISC системы команд](https://github.com/bilyardvmetro/CSA-Lab4)

> Go, Python, Github CI

Проект позволяет писать программы на ASM-Like языке RISC системы команд, транслировать их в бинарные файлы для эмулятора и затем выполнять эти файлы на эмуляторе процессора. 

## Репозиторий с моими работами из университета ИТМО

- [ITMO-System-Application-Software](https://github.com/bilyardvmetro/ITMO-System-Application-Software)
