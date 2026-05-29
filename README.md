Markdown
# Онлайн-каталог детской одежды «KidsShop»

[![Maintainability](https://qlty.sh/gh/alvmni/projects/kids_catalog/maintainability.svg)](https://qlty.sh/gh/alvmni/projects/kids_catalog)
![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![Django](https://img.shields.io/badge/django-5.2-green.svg)

KidsShop — это веб-приложение для интернет-магазина детских пижам и повседневной одежды. Проект разработан в рамках дипломной работы (Hexlet) и демонстрирует работу с базами данных, маршрутизацией, сессиями и шаблонизатором. В перспективе проект служит базой для независимой торговой площадки.

## 🚀 Демонстрация работы
<video src="docs/demo.mp4" controls="controls" width="100%"></video>
## 🛠 Стек технологий
* **Backend:** Python, Django 5.2
* **Frontend:** HTML5, CSS3, Bootstrap 5.3
* **База данных:** SQLite
* **Архитектура:** MVT (Model-View-Template)

## ⚙️ Основной функционал
- [x] Просмотр каталога товаров с пагинацией.
- [x] Глобальный поиск по названиям и описаниям.
- [x] Фильтрация одежды по категориям.
- [x] Корзина покупок на базе клиентских сессий (без обязательной регистрации).
- [x] Оформление заказа с сохранением данных клиента в базу.
- [x] Панель администратора для управления товарами.

## 💻 Установка и запуск локально

1. Клонируйте репозиторий:
```bash
git clone [https://github.com/alvmni/kids_catalog.git](https://github.com/alvmni/kids_catalog.git)
cd kids_catalog