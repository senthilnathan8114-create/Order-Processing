# Order Processing

Full-stack concurrent order processing application.

- `frontend/`: React + Vite dashboard
- `backend/`: Java 17 + Spring Boot application with MySQL

## Setup

1. Install Java 17, Maven, Node.js, and MySQL.
2. Create a MySQL database or let the configured JDBC URL create `orderdb` (if permitted).
3. Set the environment variable `DB_PASSWORD` to your local MySQL password. Optionally set `DB_URL` and `DB_USERNAME`.
4. In `backend/`, run `mvn spring-boot:run`.
5. In `frontend/`, run `npm install` and then `npm run dev`.

Dependencies, generated artifacts, old Git history and secrets are not included in this source archive. Run `git init` in the extracted project root before your first push.
