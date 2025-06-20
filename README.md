# CommDataBase
Логическая модель данных “Онлайн торговля” 

![изображение](https://github.com/user-attachments/assets/b5c9c74b-477b-4102-a3bf-cfe9703bb52f)

Работа над итоговым заданием была разбита на несколько ключевых этапов:
1.	Анализ предметной области и проектирование структуры данных
Определены сущности, их атрибуты, связи (один-ко-многим, многие-ко-многим), проанализированы требования к хранилищу информации.
2.	Создание базы данных и таблиц с использованием SQL-команд CREATE DATABASE, CREATE TABLE реализована схема. Определены первичные и внешние ключи, типы данных, ограничения (CHECK, NOT NULL, UNIQUE).
3.	Наполнение базы данных
С помощью команд INSERT INTO добавлены тестовые данные. Использовались также UPDATE, DELETE для демонстрации операций редактирования и удаления.
4.	Формирование запросов
Написаны простые и сложные запросы, включая агрегатные функции (SUM, COUNT), фильтрацию, сортировку, группировку, подзапросы и объединения таблиц (JOIN всех видов).
5.	Дополнительные функции
Созданы представления (VIEW) для удобной выборки данных, функции (FUNCTION) на языке SQL.
6.	Администрирование и безопасность
Реализовано создание ролей и пользователей, предоставление прав доступа (GRANT, REVOKE). Выполнено резервное копирование с использованием pg_dump, восстановление базы — через pg_restore.

