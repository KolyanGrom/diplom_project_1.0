# Отчет о проведенной работе с веб-сервисом:

[План тестирования](https://github.com/KolyanGrom/diplom_project_1.0/blob/main/documents/Plan.md)

[Отчет по итогам тестирования](https://github.com/KolyanGrom/diplom_project_1.0/blob/main/documents/Report.md)

[Итоговые результаты](https://github.com/KolyanGrom/diplom_project_1.0/blob/main/documents/Result.md)

# Инструкция активации проекта:

## На ПК необходимо установить десктопные версии приложений:

1. Intelij IDEA
2. Браузер: Версия 125.0.6422.142 (Официальная сборка), (64 бит)
3. Docker Desktop Current version: 4.29.0 (145265)

## Инструкция по запуску автотестов:

1. Проверить, что порты 8080, 9999, 5432 или 3306 (в зависимости от выбранной СУБД) свободны
2. Склонировать репозиторий https://github.com/KolyanGrom/diplom_project_1.0
3. Открыть его в Intelij IDEA
4. Ввести в терминале команду `docker-compose up`
5. Для запуска с поддержкой
    - *СУБД MySQL*:
        - Ввести в терминале команду `java -jar ./artifacts/aqa-shop.jar`
        - Нажать `ctrl` дважды - открыть окно Run anything. Ввести команду `gradlew clean test`
    - *СУБД PostgreSQL*:
        - Ввести в терминале
          команду ` java "-Dspring.datasource.url=jdbc:postgresql://localhost:5432/app" -jar artifacts/aqa-shop.jar`
        - Нажать `ctrl` дважды - открыть окно Run anything. Ввести
          команду `gradlew clean test "-Ddb.url=jdbc:postgresql://localhost:5432/app"`
9. Для генерации Allure отчета нажать: gradle-verification-allureServe
