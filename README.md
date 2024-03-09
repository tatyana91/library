# Проект "Библиотека"

## Технологии

Бэкенд: PHP 8.2.16, PostgreSQL, Nginx 1.25.4

## Настройка и запуск проекта

### Запуск контейнеров Docker:

`docker-compose up -d --build`

### Запуск команд внутри контейнера:

`docker-compose exec php-fpm bash`

#### Установка Laravel зависимостей:

`composer install`

#### Настройка переменных среды:

`cp .env.example .env`

#### Генерация ключа приложения:

`php artisan key:generate`