# Домашнее задание к занятию "`Очереди RabbitMQ`" - `Корнилов Арсений`

---
### Задание 1. Установка RabbitMQ
Используя Vagrant или VirtualBox, создайте виртуальную машину и установите RabbitMQ. Добавьте management plug-in и зайдите в веб-интерфейс.

ОТВЕТ: <img width="2490" height="902" alt="image" src="https://github.com/user-attachments/assets/692074b8-9447-4fa4-8cd2-2039b8d8c9b8" />


### Задание 2. Отправка и получение сообщений
Используя приложенные скрипты, проведите тестовую отправку и получение сообщения.
<img width="1702" height="1150" alt="image" src="https://github.com/user-attachments/assets/13d7caa9-3409-4124-bba8-c74a723de511" />
<img width="614" height="50" alt="image" src="https://github.com/user-attachments/assets/f60488fd-6e0c-4ad7-ad0d-b53f39e087e8" />


### Задание 3. Подготовка HA кластера
Используя Vagrant или VirtualBox, создайте вторую виртуальную машину и установите RabbitMQ. Добавьте в файл hosts название и IP-адрес каждой машины, чтобы машины могли видеть друг друга по имени.
Затем объедините две машины в кластер и создайте политику ha-all на все очереди.

В качестве решения домашнего задания приложите скриншоты из веб-интерфейса с информацией о доступных нодах в кластере и включённой политикой.
<img width="1587" height="160" alt="image" src="https://github.com/user-attachments/assets/4588beb6-7058-42d5-9254-da800a07ef9b" />
<img width="1105" height="206" alt="image" src="https://github.com/user-attachments/assets/2dd5f802-c96a-4d53-af55-6e039ccb58f8" />

Также приложите вывод команды с двух нод:
<img width="1732" height="1128" alt="image" src="https://github.com/user-attachments/assets/d22765f1-0411-4821-a312-609fe6c6d486" />
<img width="1963" height="1136" alt="image" src="https://github.com/user-attachments/assets/b2789c98-5770-489e-abd5-04f67acdd0ab" />
