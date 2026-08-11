# UC-21 Create Skill
## Related User Stories
US04 – Управление навыком
## Template
Based on the [Create Entity Template](./templates/Create-Entity-Template.md)
## Extensions to Main Scenario
- На этапе ввода данных (шаг 3 шаблона) пользователь выбирает траекторию, к которой будет привязан навык, из списка существующих.
- Пользователь может указать область знаний навыка.
## Linked Entities
- Trajectory
- Action
- Skill area
## Business Rules
- BR-1 Название навыка должно быть уникальным в пределах одной траектории.
- BR-2 Навык должен быть привязан к одной траектории.
- BR-3 Допустимые значения типа навыка: basic (ключевой) и additional (дополнительный).
- BR-4 Связь навыка с областью знаний является необязательной.

