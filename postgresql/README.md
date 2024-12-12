<p align="center">
  <img src="/img.shields.io/image/postgresql-logo.png" width="500" alt="Capa" /></a>
</p>

## 📝 Challenges

You are taking your first steps in using containers. And the best way to get started in the world of containers is to use them in a development environment.

Your mission is to help the development team have more autonomy in developing projects. And one of the team's complaints is the local setup.

Create a command to create a PostgreSQL database in the developer environment in a way that meets the following requirements:

The database name must be **curso_docker**
The database access user must be **docker_usr**
The user password must be **docker_pwd**

Remember that running in a container must be transparent to whoever is developing. And here you don't need to worry about losing database data or anything like that, it is just for specific development.

---

## 🏷️ Command line

> Start the application:
> ```console
> $ docker container run -d --name postgresql_challenge -p 5432:5432 -e POSTGRESQL_PASSWORD="docker_pwd" -e POSTGRESQL_DATABASE="curso_docker" -e POSTGRESQL_USERNAME="docker_usr" bitnami/postgresql
> ```

---

## 📦️ Alternative

If you want to use the docker-compose.yml file, just run the command below

> Start the application:
> ```console
> $ docker compouse up -d
> ```

---