**Установка**
Скопировать директорию helm-chart и выполнить из нее команду:
helm install webapi .
После установки по адресу http://arch.homework/swagger/index.html будет достпен Swagger.
По адресу http://arch.homework/hc будет доступен health check
**Тесты**
Postman коллекция находится в папке Postman.
Для проверки выполнить команду: newman run Users\ API.postman_collection.json
**Удаление**
Для удаления достаточно выполнить команду: 
helm uninstall webapi
