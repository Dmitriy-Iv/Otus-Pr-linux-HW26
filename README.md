# **Введение**

В данном домашнем задании нам необходимо поработать с динамическим вебом.

---
- Для выполнения данного ДЗ, необходимо скачать стенд и запустить его.

```
git clone https://github.com/Dmitriy-Iv/Otus-Pr-linux-HW26.git
cd Otus-Pr-linux-HW26/
vagrant up
```

В результате у нас будет создан виртуальный сервер - DynamicWeb, на которую будут редиректиться три порта с хостовой машины: 8081, 8082, 8083. С помощью ansible установим на него docker и docker-compose, и запустим docker-compose файл. В нём у нас описаны 5 контейнеров: nginx, wordpress, database, node, app. Вышеописанные порты мы пробрасываем далее в контейнер nginx, а в нём в конфигурационном файле уже описываем, куда дальше - на какой из сервисов редиректить порты.
Все конфигурационные файлы описаны в методичке, так что они просто копировались без особых изменений.

- Проверка:
![alt text](/project/screens/django.PNG?raw=true "Screenshot1")  
![alt text](/project/screens/node js.PNG?raw=true "Screenshot2")  
![alt text](/project/screens/wordpress.PNG?raw=true "Screenshot1")  
