Выполнить следующие команды после клонирования
(выполнять из текущей директории)

docker exec -it backend npx prisma migrate dev
docker exec -it database pg_restore -U edward -d xxxpc pg_data/xxxpc_db_data_restore.dump
