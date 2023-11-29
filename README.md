# Домашнее задание к занятию «Кеширование Redis/memcached»

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*

### Решение 1

*Во-первых, применение кэширования увеличивает производительность системы: доступ к наиболее востребованным данным, находящимся в кэше, осуществляется намного быстрее (очевидно, что забрать данные из ячейки ОЗУ можно намного быстрее, чем из сектора диска.* 
   
*Как следствие, с точки зрения клиента (абонента, пользователя и т.п.) резко сокращается время ответа на запросы.* 
   
*В highload-системах обязательной к применению является практика прогнозирования пиков нагрузки и сглаживания её за счет помещения часто запрашиваемых данных в кэш. Был рассмотрен пример с онлайн-магазинами и "черной пятницей". Так же могу предположить, что такой подход широко применяется в поисковых сервисах, или, например, на фондовых биржах и проч.*


---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

### Решение 2

---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

### Решение 3

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

### Решение 4
