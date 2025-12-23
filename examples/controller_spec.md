# UserController

## Responsibility
Обрабатывает HTTP-запросы, связанные с пользователями.

## Inputs
- HTTP-запрос создания пользователя

## Outputs
- HTTP-ответ с результатом операции

## Business Rules
1. Контроллер не содержит бизнес-логики
2. Все решения делегируются usecase

## Flow
1. Принимает запрос
2. Вызывает CreateUserUseCase  
   → calls: ../usecases/create_user.md

## Dependencies
- [CreateUserUseCase](../usecases/create_user.md)

## Errors
- ErrInvalidRequest
