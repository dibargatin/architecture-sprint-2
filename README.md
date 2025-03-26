# pymongo-api

Диаграмма решения представлена в файле [arch-diagram.drawio](./arch-diagram.drawio)

## Как запустить

Для запуска и настройки приложения выполните инструкцию [Задания 3](./mongo-sharding-repl/README.md), перейдя в рабочий каталог `./sharding-repl-cache`.

## Как проверить

### Если вы запускаете проект на локальной машине

Откройте в браузере http://localhost:8080

### Если вы запускаете проект на предоставленной виртуальной машине

Узнать белый ip виртуальной машины

```shell
curl --silent http://ifconfig.me
```

Откройте в браузере http://<ip виртуальной машины>:8080

## Доступные эндпоинты

Список доступных эндпоинтов, swagger http://<ip виртуальной машины>:8080/docs