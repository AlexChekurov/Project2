# Моя реализация Project 2 на Spring
Проходя курс по Spring от преподавателя Наиля Алишева на платформе Udemy (https://www.udemy.com/course/spring-alishev/), мне приходилось самостоятельно выполнять технические задания, совершенствуя свои навыки. Делюсь результатами выполнения в этом репозитории

Задание:

![Project2_TZ-02](https://user-images.githubusercontent.com/101993583/235651363-2fdd14f1-3297-42d4-9f9f-e23d54d87f57.png)
![Project2_TZ-03](https://user-images.githubusercontent.com/101993583/235651413-d5fae905-f826-4294-9041-95783a86e4c9.png)
![Project2_TZ-04](https://user-images.githubusercontent.com/101993583/235651457-e9127c50-eb3a-4fb7-8ffe-352dd3e95bda.png)
![Project2_TZ-05](https://user-images.githubusercontent.com/101993583/235651476-d44a4543-d1cc-478a-9427-a7e3cca09baf.png)
![Project2_TZ-06](https://user-images.githubusercontent.com/101993583/235651487-05251367-1515-46e8-8645-09cf4f5d14d8.png)
![Project2_TZ-07](https://user-images.githubusercontent.com/101993583/235651497-e83c8030-8495-45c8-8f29-a95d09f40420.png)
![Project2_TZ-08](https://user-images.githubusercontent.com/101993583/235651517-544bb063-014d-4673-b24b-37f1d8706015.png)
![Project2_TZ-09](https://user-images.githubusercontent.com/101993583/235651534-9ae3fff7-2012-4593-8615-b1f7ff1cad66.png)

Задание было выполнено полностью в соотвествии с поставленными требованиями. Приложение запускается на Tomcat-10, разворачивается в контекстном пути http://localhost:8080/people

Использованные технологии: Java 17 SE, Apache Maven, Apache Tomcat, PostgreSQL, Hibernate, Spring Core, Spring MVC, Spring Data, Thymeleaf, HTML, CSS.

SQL код для создания таблиц находится в файле sql/project1_db.sql

Пример работы:

Пагинация:

https://user-images.githubusercontent.com/101993583/235653626-d11d5f46-3d94-46f2-bf8e-fdaaa8278eff.mov

SQL код, который нужен для того, чтобы вручную назначить Timestamp:
```
UPDATE Book SET taken_at='2021-05-07 08:00:00' WHERE id=1;
```
