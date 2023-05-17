# Сервис доставки
Реализует возможности: создание курьеров и заказов, отметка выполнениных заказов, расчет заработка и рейтинга курьера, эффективная система распределния заказов на рабочий день

Покрыт интеграционными тестами

Заказ может иметь несколько возможных интервалов доставки в день, курьер может иметь несколько возможных рабочих интервалов в день. 
Распределение заказов может обьединять несколько заказов в одну доставку. Вес, количество заказов, количество посещенных районов за одну доставку для каждого типа курьеров ограничено.

Настроен ratelimmiter

## Используемые технологии
fast-api, sqlalchemy, postgresql, docker, pytest
