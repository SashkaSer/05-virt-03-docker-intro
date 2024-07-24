# Домашнее задание к занятию 4 «Оркестрация группой Docker контейнеров на примере Docker Compose» - `Сергиенко А`

### Задание 1
Кастомная страница Nginx  
![task1](https://github.com/SashkaSer/05-virt-03-docker-intro/blob/main/img/webpage.png)`

Образ в DockerHub
<https://hub.docker.com/repository/docker/sashaser/custom-nginx/general>

Dockerfile
```
FROM nginx:1.21.1
COPY ./index.html /usr/share/nginx/html/index.html
```
---

### Задание 2  
![task2](https://github.com/SashkaSer/05-virt-03-docker-intro/blob/main/img/task2.png)`
