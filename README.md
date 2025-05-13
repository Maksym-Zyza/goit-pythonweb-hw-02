# FastAPI + PostgreSQL

## 📦 Віртуальне середовище (Virtual Env)

1. **Створення:**

   ```bash
   python3 -m venv env
   ```

2. **Активація:**
   ```bash
   source env/bin/activate
   ```

## 🚀 Використання Docker

### Створення Docker image:

1. Створюємо `Dockerfile`.
2. Будуємо Docker image:
   ```bash
   docker build -t <name> .
   ```

### Перевірка існуючих images:

1. Список всіх Docker images:

   ```bash
   docker images
   ```

2. Список контейнерів (включаючи зупинені):
   ```bash
   docker ps -a
   ```

### Запуск контейнера:

1. Запуск контейнера:

   ```bash
   docker run -p <host_port>:<container_port> -d <name>
   ```

2. Запуск зупиненого контейнера:

   ```bash
   docker start <name|hash>
   ```

3. Зупинка контейнера:

   ```bash
   docker stop <name|hash>
   ```

4. Перегляд логів контейнера:
   ```bash
   docker logs <name|hash>
   ```

### Використання Docker Compose:

1. Створюємо файл `docker-compose.yaml`.
2. Запуск Docker Compose:
   ```bash
   docker compose up
   ```
