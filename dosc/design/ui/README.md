# User Interface Design
This section contains the user interface design artifacts for the Skills Map application, including wireframes, navigation, and traceability to functional requirements.
## Design Goals
The interface is designed to support personal management of learning trajectories, skills, and actions.
The main UI goals are:
- provide intuitive navigation between main entities;
- support creating and managing learning trajectories;
- support searching and filtering of skills and actions;
- make relationships between skills and actions easy to understand.

## Wireframes
Wireframes describe the main application screens and user interactions. Included screens:
### Authentication and Home Page
- [Sign In Form](./screens/login.png)
- [Home Page](./screens/login.png)
- [Sign Out Confirmation Modal](./screens/login.png)
### Trajectory and Skill Management
- [Trajectory List](./screens/login.png)
- [Create and Edit Trajectory Form](./screens/login.png)
- [Trajectory Details](./screens/login.png)
- [Delete Confirmation Modal Example](./screens/login.png)
- [Create and Edit Skill Form](./screens/login.png)
- [Skill Details](./screens/login.png)
### Action Management
- [Action List](./screens/login.png)
- [Create and Edit Action Form](./screens/login.png)
- [Action Details](./screens/login.png)
- [Add Skill to Action](./screens/login.png)

## Dialogue Map
The dialogue map shows navigation between application screens, dialogs, and user interactions.  
See [Dialogue Map](./dialogue-map.png).

## Traceability
The table below shows the relationship between functional requirements and the corresponding user interface screens.

| User Story | Related UI |
|------------|------------|
| US01 Create Trajectory | Trajectory Create Screen |
| US04 Manage Skill | Skill List, Skill Details, Skill Edit |
| US05 Add Action and Resource | Action Create Screen |
| US06 View Skill Actions | Skill Details Screen |
