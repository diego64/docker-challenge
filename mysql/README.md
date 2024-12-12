<p align="center">
  <img src="/img.shields.io/image/mysql-logo.png" width="500" alt="Capa" /></a>
</p>

## 📝 Challenges

Create the command to create the MySQL database using the requirements below:

The database name must be **docker_db**
The database access user must be **docker_usr**
The user password must be **docker_pwd**

Remember that running in a container must be transparent to whoever is developing. And here you don't need to worry about losing database data or anything like that, it's just for specific development.

---

## 🏷️ Command line

> Start the application:
> ```console
> $ docker container run -d --name mysql_challenge -p 3306:3306 -e MYSQL_ROOT_PASSWORD="123456" -e MYSQL_DATABASE="docker_db" -e MYSQL_USER="docker_usr" -e MYSQL_PASSWORD="docker_pwd" mysql
> ```

---

## 📦️ Alternative

If you want to use the docker-compose.yml file, just run the command below

> Start the application:
> ```console
> $ docker compouse up -d
> ```

---