# UC-S2 Log Out
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
Выход из системы Skills Map.
## Actor
Пользователь (User)
## Trigger
Пользователь инициирует выход из системы.
## Preconditions
- PRE-1 Пользователь аутентифицирован и находится в системе.
## Postconditions
- POST-1 Success Guarantee: Пользователь вышел из системы, доступ к защищенным разделам системы прекращен.
- POST-2 Minimal Guarantee: В случае ошибки состояние системы не изменяется.
## Main Scenario
1. Пользователь выбирает опцию выхода из системы.
2. Система запрашивает подтверждение выхода.
3. Пользователь подтверждает действие.
4. Система прекращает доступ пользователя к системе.
5. Система возвращает пользователя на страницу входа или отображает сообщение о выходе.
## Alternative Scenarios and Extensions
- 3a. Отмена выхода
1. Пользователь отменяет выход из системы.
2. Система прекращает выполнение сценария.
3. Выход из системы не выполняется.
## Exceptions
E1 Системная ошибка (на шаге 4)
1. Система не может выполнить выход по технической причине.
2. Система отображает сообщение о невозможности выхода.
3. Сценарий завершается.
## Linked Entities
None
## Business Rules
None
## Notes
Данный сценарий описывает процесс выхода пользователя из системы.
