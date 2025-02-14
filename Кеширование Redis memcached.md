# Домашнее задание к занятию «Кеширование Redis/memcached»


### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 


В основном кеширование данных используется для быстрого доступа к ним и уменьшения времени простоя. 


*Приведите ответ в свободной форме.*

---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*
![image](https://github.com/nikotin8899/home-lab/assets/56605975/4a94aa16-ed98-40db-ad1d-fd9c04f80bc0)


---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*


![image](https://github.com/nikotin8899/home-lab/assets/56605975/dc5ff0a1-324b-429c-9b5a-ffa540aa6cb5)

Тяжело было успеть создать его и сразу же получить данные до удаления, так что только один)



---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*
![image](https://github.com/nikotin8899/home-lab/assets/56605975/71e16106-9de3-4ffb-b149-82222ef3eb64)



## Дополнительные задания (со звёздочкой*)
Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже разобраться в материале.

### Задание 5*. Работа с числами 

Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.  

*Приведите скриншот, где будут проделаны все операции и будет видно, что значение key5 стало равно 10.*

![image](https://github.com/nikotin8899/home-lab/assets/56605975/757fdade-8d93-4b1b-a7a1-3f01facafa23)
