# PomodoroEducation

PomodoroEd: Empowering Education with Pomodoro Technique-Based Learning Platform for Content Management, Timer, Assessment, and Analytics.

# Project Instructions

## Backend - Django

1. Move directory (from root directory)

```bash
  cd server
```

2. Create a virtual environment

```bash
  python -m venv venv
```

3. Activate a virtual environment

```bash
  source venv/bin/activate
```

4. Install dependencies

```bash
  pip install -r requirements.txt
```

5. Run PostgreSQL db via Docker

```bash
  docker compose up
```

6. Run migration

```bash
  python manage.py makemigrations
  python manage.py migrate
```

7. Run backend server

```bash
  python3 manage.py runserver / python manage.py runserver
```

## Frontend - ViteJS

1. Move directory (from root directory)

```bash
  cd client
```

2. Install dependencies

```bash
  npm install
```

3. Run

```bash
   npm run build
   npm run start
```
