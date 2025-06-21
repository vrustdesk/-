# Домашнее задание к занятию «Кластеризация и балансировка нагрузки» - Иванов Владислав

Задание 1
Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

Задание 2
Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.



Решение 

Задание 1

Запустил 2 simlpe python сервера на разных протах
![image](https://github.com/user-attachments/assets/0afda30b-7a75-4b06-95e9-0770794668f9)

Конфигурационный файл haproxy.cfg
https://github.com/vrustdesk/-/blob/main/1)%20haproxy.cfg

Скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy
![image](https://github.com/user-attachments/assets/e0f45d2c-3447-49c6-b345-2c739c73eff9)


Задание 2

Запустил 3 simlpe python сервера на разных протах
![image](https://github.com/user-attachments/assets/02ee426a-d43c-4062-ad3f-ed6e40f16aa5)

Конфигурационный файл haproxy.cfg
https://github.com/vrustdesk/-/blob/main/2)%20haproxy.cfg

Cкриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена 
example.local

![image](https://github.com/user-attachments/assets/194ca261-c7bb-4215-a102-5b4c3216c4f4)

и без него

![image](https://github.com/user-attachments/assets/f039c1a8-50b4-43ad-918d-edaa71ad9b91)
