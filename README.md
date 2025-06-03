# 🛍️ Django Shop — учебный интернет-магазин

Это один из первых моих проектов на **Django**, в котором реализованы базовые возможности интернет-магазина с системой авторизации пользователей.

## 🚀 Возможности

- 👤 Регистрация и авторизация
- 📦 Управление товарами
- 🔐 Разделение логики по приложениям (`authentication`, `shop`)
- 🧱 Модели, миграции, админ-панель

## 🧰 Стек технологий

- Python 3
- Django 4.x
- SQLite (по умолчанию)
- Django Admin

## 🗂️ Структура проекта

- `authentication/` — система авторизации
- `shop/` — модели, представления и логика магазина
- `main/` — настройки и конфигурация проекта
- `manage.py` — основной управляющий скрипт

## 📦 Установка и запуск

### 1. Клонировать репозиторий
```bash
git clone https://github.com/your-username/django-shop.git
cd django-shop
```

### 2. Установить зависимости
```bash
pip install -r requirements.txt
```

### 3. Применить миграции
```bash
python manage.py makemigrations
python manage.py migrate
```

### 4. Запустить сервер
```bash
python manage.py runserver
```

## 📬 Автор

- 💼 Usman Gamidov
- Telegram: [@At_taqwa_tw](https://t.me/At_taqwa_tw)

---

🧠 Проект создан в рамках обучения Django и MVC-архитектуре.
