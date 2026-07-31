# UC-S1 Log In
## Related User Stories
None
## Contents
- [User Goal](#user-goal)
- [Actor](#actor)
- [Trigger](#trigger)
- [Preconditions](#preconditions)
- [Postconditions](#postconditions)
- [Main Scenario](#main-scenario)
- [Alternative Scenarios and Extensions](#alternative-scenarios-and-extensions)
- [Exceptions](#exceptions)
- [Linked Entities](#linked-entities)
- [Business Rules](#business-rules)
- [Notes](#notes)
## User Goal
Аутентификация пользователя и получение доступа к системе Skills Map.
## Actor
Пользователь (User)
## Trigger
Пользователь инициирует вход в систему.
## Preconditions
None
## Postconditions
- POST-1 Success Guarantee: Пользователю предоставлен доступ к системе.
- POST-2 Minimal Guarantee: В случае ошибки состояние системы не изменяется.
## Main Scenario
1. Система отображает форму входа.
2. Пользователь вводит логин и пароль.
3. Система проверяет формат логина и пароля.
4. Система проверяет соответствие логина и пароля зарегистрированным учетным данным (аутентификация).
5. Система предоставляет пользователю доступ к системе.
## Alternative Scenarios and Extensions
- 3а. Ошибка формата учетных данных
1. Система обнаруживает нарушение формата учетных данных.
2. Система отображает сообщение об ошибке.
3. Возврат к шагу 2.
- 4а. Ошибка аутентификации: учетные данные не совпадают с зарегистрированными
1. Система обнаруживает несоответствие учетных данных.
2. Система отображает сообщение об ошибке.
3. Возврат к шагу 2.
## Exceptions
E1 Системная ошибка (при обработке запроса)
1. Происходит технический сбой.
2. Система фиксирует ошибку.
3. Система отображает сообщение о невозможности входа.
4. Сценарий завершается.
## Linked Entities
- User
## Business Rules
None
## Notes
Данный сценарий описывает процесс аутентификации пользователя.

