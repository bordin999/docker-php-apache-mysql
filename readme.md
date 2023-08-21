# My docker
we have php apache mysql and phpmyadmin in one container
## port for work
- 8000 to phpmyadmin
- 8080 to apache
- 9906 to mysql
## how to use
- clone this repository
- run `docker-compose up -d`
- open `localhost:8080` in your browser
- open `localhost:8000` in your browser
- login to phpmyadmin with `root` and `MYSQL_ROOT_PASSWORD` as login and password
- enjoy

### craete new project in folder
- create new folder in `php/src` folder
- create new file `index.php` in your folder
- write some php code in `index.php`
- open `localhost:8080/your_folder_name` in your browser
- enjoy