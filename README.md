# Задание: Разработать приложение для управления пользователями (CRUD) с RESTful интерфесом:
1. Реализована поддержка операций управления (создания, чтения, редактирования, удаления) пользователями, которые определяются значениями: id, имя, фамилия, дата рождения.
2. Приложение собирается при помощи maven.
3. Система хранения данных в JSON файле. 

### Программа содержит:
1. Класс "ServingWebContentApplication", в котором происходит запуск Spring-приложения и чтение данных (пользователей) из файла.   
2. Класс "UsersController", в которм идет обработка запросов от пользователя (методы PUT, POST, DELETE, GET).
3. Класс "StorageProcessing", в котором осуществляются операции с базой данных, напрмер, запись новых пользователей в файл.
4. Класс "User" для описания пользователей.
5. Тесты для проверки работы с базой данных и работоспособности поднятого приложения.