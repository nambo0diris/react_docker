**Как запустить проект:**
1. Установить docker и git, например, на vds 
2. Скачать туда проект
3. `cd react_docker`
4. Создать docker-образ `docker build -t react_docker_image .`
5. `docker run -p -d <ip по которому доступен vds>:<port>:80 react_docker_image`
