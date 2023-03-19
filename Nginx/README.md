Произвести замену стартовой страницы Nginx командой 
docker run --name=test1 -p 7000:80 -d -v /home/user/Docker/Nginx:/usr/share/nginx/html nginx
Где /home/user/Docker/Nginx путь к файлу html