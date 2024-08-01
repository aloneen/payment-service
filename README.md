# Payment Service

Payment Service is a Spring Boot application for managing payment transactions.

## Features

- Create Payment
- Check Payment Status
- Update Payment Status

## Requirements

- Java 11 or higher
- MySQL

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/<your-github-username>/payment-service.git
    cd payment-service
    ```

2. **Build the project**:
    ```sh
    mvn clean package
    ```

3. **Run the application**:
    ```sh
    java -jar target/payment-service-0.0.1-SNAPSHOT.jar
    ```

4. **Docker**:
    ```sh
    docker build -t payment-service .
    docker run -p 8080:8080 payment-service
    ```

## Usage

1. **Create Payment**:
    - Endpoint: `POST /payments`
    - Body: `{ "amount": 100.00 }`

2. **Get All Payments**:
    - Endpoint: `GET /payments`

3. **Get Payment by ID**:
    - Endpoint: `GET /payments/{id}`

4. **Update Payment Status**:
    - Endpoint: `PUT /payments/{id}?status=COMPLETED`

## Contributing

Feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.


# Сервис Платежей

Сервис Платежей - это приложение на Spring Boot для управления платежными транзакциями.

## Возможности

- Создание платежа
- Проверка статуса платежа
- Обновление статуса платежа

## Требования

- Java 11 или выше
- MySQL

## Установка

1. **Клонировать репозиторий**:
    ```sh
    git clone https://github.com/<your-github-username>/payment-service.git
    cd payment-service
    ```

2. **Собрать проект**:
    ```sh
    mvn clean package
    ```

3. **Запустить приложение**:
    ```sh
    java -jar target/payment-service-0.0.1-SNAPSHOT.jar
    ```

4. **Docker**:
    ```sh
    docker build -t payment-service .
    docker run -p 8080:8080 payment-service
    ```

## Использование

1. **Создание платежа**:
    - Эндпоинт: `POST /payments`
    - Тело запроса: `{ "amount": 100.00 }`

2. **Получение всех платежей**:
    - Эндпоинт: `GET /payments`

3. **Получение платежа по ID**:
    - Эндпоинт: `GET /payments/{id}`

4. **Обновление статуса платежа**:
    - Эндпоинт: `PUT /payments/{id}?status=COMPLETED`

## Вклад

Не стесняйтесь отправлять запросы на исправление и пул-реквесты. Для крупных изменений, пожалуйста, сначала откройте задачу, чтобы обсудить, что вы хотите изменить.


