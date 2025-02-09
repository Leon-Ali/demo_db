# demo_db
Демо база для туториалов

1. Скачать дамп по ссылке: https://edu.postgrespro.ru/demo-medium.zip
2. Взять файл из архива, переименовать в demo_db.sql и положить в папку где лежит docker-compose.yaml
3. Запустить композ командой: docker-compose up -d
4. Загрузить дамп командой: docker-compose exec -i db psql -U postgres -f demo_db.sql
