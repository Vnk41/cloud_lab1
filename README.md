В данной лабораторной работе было необходимо запустить приложение с помощью Docker. Для примера взято приложение из первой лабораторной работы, считающее обращения по адресам. 

Сначала приложение запускается в Docker, параметры запуска указаны в файле Dockerfile, затем при помощи 
Docker-Compose (параметры указаны в файле docker-compose.yaml) создается набор контейнеров.

Команды для запуска приложения в Docker:
sudo docker build -t -test .
sudo docker run -dp 8081:8080 test

Команды для Docker-Compose:
sudo docker build
sudo docker-compose up

Полученный результат:
![alt text](Screenshot%20(2).png)
![alt text](Screenshot%20(3).png)
![alt text](Screenshot%20(4).png)
![alt text](Screenshot%20(5).png)
