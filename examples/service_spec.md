# EmailService

## Responsibility
Отправляет email-сообщения пользователям.

## Inputs
- Email получателя
- Тип сообщения

## Outputs
- Результат отправки

## Business Rules
1. Email отправляется асинхронно
2. Ошибка отправки логируется

## Flow
1. Формирование письма
2. Отправка через внешний сервис

## Dependencies
- Внешний email-провайдер

## Errors
- ErrEmailSendFailed
