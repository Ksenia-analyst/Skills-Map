# UC-36 Unlink Skill from Action
## Related User Stories
None (supports US06 – Просмотр действий навыка)
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
Пользователь удаляет связь навыка с действием.
## Actor
Пользователь (User)
## Trigger
Пользователь инициирует удаление навыка из действия через интерфейс системы.
## Preconditions
- PRE-1 Пользователь аутентифицирован.
- PRE-2 Пользователь находится в интерфейсе управления действиями.
- PRE-3 У действия есть связанные навыки.
## Postconditions
- POST-1 Success Guarantee: Связь между выбранным действием и навыком удалена.
- POST-2 Minimal Guarantee: В случае ошибки состояние системы не изменяется.
## Main Scenario
1. Пользователь выбирает операцию удаления навыка из действия.
2. Система запрашивает подтверждение удаления.
3. Пользователь подтверждает действие.
4. Система удаляет связь между действием и навыком.
5. Система отображает обновленный список связанных навыков действия.
## Alternative Scenarios and Extensions
- 2a. Отмена удаления
1. Пользователь отменяет удаление навыка из действия.
2. Система прекращает выполнение сценария.
3. Связь не удаляется.
## Exceptions
E1 Системная ошибка (на шаге 4)
1. Происходит технический сбой при удалении связи.
2. Система фиксирует ошибку.
3. Система отображает сообщение о невозможности завершить операцию.
4. Сценарий завершается.
## Linked Entities
- Skill
- Trajectory (indirectly via Skill)
## Business Rules
None
## Notes
Данный сценарий реализует удаление связи many-to-many между сущностями навык и действие в контексте действия.
