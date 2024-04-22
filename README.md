# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Тен Денис`


### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*

### Решение Задание 1. Кеширование 

Кеширование - это механизм, который используется для временного хранения данных в быстродействующей памяти с целью ускорения доступа к этим данным. Кеширование может решить ряд проблем, связанных с производительностью и эффективностью работы программы или системы. Например:

1. Увеличение скорости доступа к данным: Кеширование позволяет хранить часто используемые данные в памяти, что позволяет значительно сократить время доступа к этим данным. Например, веб-сервер может кешировать результаты выполнения запросов к базе данных, чтобы избежать повторного выполнения одних и тех же запросов и ускорить обработку запросов пользователей.

2. Сокращение нагрузки на ресурсы: Кеширование может помочь снизить нагрузку на ресурсы системы, такие как процессор или сеть. Если результаты вычислений уже кешированы, то нет необходимости повторно выполнять эти вычисления, что позволяет сэкономить ресурсы и увеличить эффективность работы системы.

3. Уменьшение задержек при повторном использовании данных: Кеширование позволяет быстро получать данные из кеша, а не запрашивать их снова. Это особенно полезно в ситуациях, когда требуется повторное использование данных в различных частях программы или системы. Например, кеширование может использоваться для хранения результатов сложных вычислений или запросов к внешним сервисам, чтобы избежать задержек, связанных с повторным выполнением этих операций.

4. Повышение отказоустойчивости: Кеширование может использоваться для сохранения резервных копий данных или результатов операций. Если исходные данные или сервис становятся недоступными, можно использовать кеш для продолжения работы или восстановления системы.

---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

### Решение Задание 2. Memcached
Установка Memcached

```
apt-get install memcached
```
Проверка
```
systemctl status memcached
```


![image](https://github.com/killakazzak/11-02-sdb-hw/assets/32342205/221b3f19-c268-42d8-bd14-a11436a6a6d7)



---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

### Решение Задание 3. Удаление по TTL в Memcached

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

### Решение Задание 4. Запись данных в Redis


## Дополнительные задания (со звёздочкой*)
Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже разобраться в материале.

### Задание 5*. Работа с числами 

Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.  

*Приведите скриншот, где будут проделаны все операции и будет видно, что значение key5 стало равно 10.*

### Решение Задание 5*. Работа с числами 


