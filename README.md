## Задание

Написать простенькое приложение с использованием билиотек Flask и sqlite. У
сервера должно быть два эндпоинта.
- На один эндпоинт разрешено делать только POST запрос. При поступлении запроса с
данными в json формате на этот эндпоинт они записываются в табилицу в базе данных
SQLite.
- На второй эндпоинт разрешено делать только GET запрос. При поступлении запроса на этот
эндпоинт из таблицы данных в базе SQLite забираются все записи и возврщаются клиенту в
json формате.

## Использованные технологии 
- Flask
- sqlite
- pytest

## Инструкция запуска 

### Через .exe файл 
В папке build-exe/dist расположен .exe файл для запуска сервера.

### Без .exe файла 
Перейдите в директорию main/app и пропишите команду:

      flask run

## Инструкция запуска тестов 
Перейдите в директорию main/tests и пропишите команду: 

      pytest -vv
