# UC-31 Create Action
## Related User Stories
- US05 – Добавление действия и ресурса
- US011 – Отметка статуса действия
## Template
Based on the [Create Entity Template](./templates/Create-Entity-Template.md)
## Extensions to Main Scenario
На этапе ввода данных (шаг 3 шаблона) пользователь указывает статус действия, а также может указать ресурс и тип действия.
## Linked Entities
- Skill
- Action type
## Business Rules
- BR-1 Допустимые значения статуса действия: draft, not_started, in_progress, completed.
