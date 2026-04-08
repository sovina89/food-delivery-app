# Food Delivery Service

## Описание
Проект представляет собой сервис агрегации и доставки еды.

## Требования
- Java 17+
- Maven 3+

## Установка и запуск

1. Клонировать репозиторий:
git clone <repo_url>

2. Перейти в папку проекта:
cd food-delivery-app

3. Собрать проект:
mvn clean install

4. Запустить приложение:
mvn exec:java -Dexec.mainClass="com.fooddelivery.App"

## Структура проекта
- src/main/java - исходный код
- src/test/java - тесты
- pom.xml - конфигурация Maven

## Тестирование
Для запуска тестов:
mvn test