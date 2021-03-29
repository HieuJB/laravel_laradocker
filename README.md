# Huong dan setup
- tai xuong https://drive.google.com/file/d/1nUijloqbemE9C5NZ2YbGlhsQBnKS4aVP/view?usp=sharing
- tao 1 thu muc trong
- vao thu muc laradock run docker
docker-compose up -d nginx redis workspace mariadb phpmyadmin
- huong dan setup project cd vao project laradock
sudo docker-compose exec workspace bash
- tao mot thu muc moi de vao project laravel 
composer create-project laravel/laravel example-app
- setup env
DB_CONNECTION=mysql
DB_HOST=mariadb
DB_PORT=3306
DB_DATABASE=happy_eyes
DB_USERNAME=root
DB_PASSWORD=root

neu chay file bi loi thi setup /
File and directory owners (User and Groups) must be laradock : laradock :

docker-compose exec workspace bash
chown -R laradock:laradock /var/www
