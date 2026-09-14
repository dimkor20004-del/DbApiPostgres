\# DbApi PostgreSQL



Проект для запуска приложения db-api с базой данных PostgreSQL через Docker.



\## Запуск



1\. Запустить PostgreSQL:



```bash

docker-compose up -d

```



2\. Запустить приложение:



```bash

java -jar ./artifacts/db-api.jar

```



3\. Открыть в браузере: http://localhost:9999/api/cards



\## Результат



![Скриншот ответа](https://github.com/dimkor20004-del/DbApiPostgres/raw/main/screenshot.png)
