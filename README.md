# drom-task2

install: `composer require darmaboroev/drom-task2`
https://packagist.org/packages/darmaboroev/drom-task2

Задание:
Необходимо реализовать клиент для абстрактного (вымышленного) сервиса комментариев "example.com". Проект должен представлять класс или набор классов, который будет делать http запросы к серверу. На выходе должна получиться библиотека, который можно будет подключить через composer к любому другому проекту.
У этого сервиса есть 3 метода: 
GET "http://example.com/comments"http://example.com/comments - возвращает список комментариев
POST  "http://example.com/comment"http://example.com/comment - добавить комментарий. 
PUT "http://example.com/comment/"http://example.com/comment/{id} - по идентификатору комментария обновляет поля, которые были в в запросе  Объект comment содержит поля: id - тип int. Не нужно указывать при добавлении. name - тип string. text - тип string.  Написать phpunit тесты, на которых будет проверяться работоспособность клиента. Сервер example.com писать не надо! Только библиотеку для работы с ним.
