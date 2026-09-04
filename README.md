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
- [REST приложение на JAX-RS](https://github.com/bilyardvmetro/OPI-Lab4)
  > Jakarta EE (JAX-RS), Hibernate, PostgreSQL, Gradle, Grafana, Prometheus, JWT
  Приложение позволяет кликать на точки по области и собирать по ним статистику. В проекте есть gradle джобы, prometheus и grafana для сбора и визуализации метрик 
- [Клиент-Серверное десктоп приложение на Java](https://github.com/bilyardvmetro/ITMO-System-Application-Software/tree/main/1%20%D0%BA%D1%83%D1%80%D1%81/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/2%20sem/Lab8)
  > Java, JavaFX, PostgreSQL, Maven
  Приложение позволяет исполнять CRUD операций над объектами, а также отображает их в GUI. Приложение поддерживает одновременную работу нескольких клиентов

## Pet проекты на Go

- [ozon-Posts-And-Comments-test-project](https://github.com/bilyardvmetro/ozon-Posts-And-Comments-test-project)
- [avito-PR-project](https://github.com/bilyardvmetro/avito-PR-project)
- [CSA-Lab4](https://github.com/bilyardvmetro/CSA-Lab4)

## Учебный репозиторий с работами из университета ИТМО

- [ITMO-System-Application-Software](https://github.com/bilyardvmetro/ITMO-System-Application-Software)
