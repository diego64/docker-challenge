<p align="center">
  <img src="/img.shields.io/image/mongodb-logo.png" width="500" alt="Capa" /></a>
</p>

## 📝 Challenges

Create the command to create the MongoDB database using the requirements below:

The database root user must be **mongo_usr**
The root user password must be **mongo_pwd**

Remember that running in a container must be transparent to whoever is developing. And here you don't need to worry about losing database data or anything like that, it's just for specific development.

---

## 🏷️ Command line

> Start the application:
> ```console
> $ docker container run -d --name mongodb_challenge -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME="mongo_usr" -e MONGO_INITDB_ROOT_PASSWORD="mongo_pwd" mongodb/atlas
> ```

---

## 📦️ Alternative

If you want to use the docker-compose.yml file, just run the command below

> Start the application:
> ```console
> $ docker compouse up -d
> ```

---