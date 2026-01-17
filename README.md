# Node.js . Домашння робота 2

Навчальний проєкт з Node.js та Express з  підключенням MongoDB через Mongoose.

- Підключення до MongoDB через `mongoose`
- Розділення логіки додатку на модулі (routes, controllers, models, middleware)


## CRUD для нотаток

Реалізовані наступні маршрути:

- `GET /notes` — отримати всі нотатки
- `GET /notes/:noteId` — отримати нотатку за ID
- `POST /notes` — створити нову нотатку
- `PATCH /notes/:noteId` — оновити нотатку за ID
- `DELETE /notes/:noteId` — видалити нотатку за ID

## Модель Note

Нотатка містить поля:
- `title` — обовʼязкове поле
- `content` — необовʼязкове
- `tag` — одне з фіксованих значень

Автоматично створюються поля `createdAt` та `updatedAt`.

Render:

https://notes-app02.onrender.com
