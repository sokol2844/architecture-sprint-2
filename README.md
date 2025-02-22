# pymongo-api


Итоговую архитектурную схему можно посмотреть в файле shema.drawio


## Как запустить

Запускаем mongodb и приложение

```shell
docker compose up -d
```

Заполняем mongodb данными и проверяем кол-во документов в репликах

```shell
./scripts/mongo-init.sh
```

