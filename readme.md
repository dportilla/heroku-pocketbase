# PocketBase Heroku

Deploy a docker image to heroku

Prerequisites
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
- [Docker](https://www.docker.com/)

## Deploy

- Create new Proyect on heroku
- Open a folder containing the Dockerfile
- Open a terminal in this folde
- Run the commands to build and deploy your proyect


```properties
heroku login

heroku container:login

heroku container:push web -a yourproyect

heroku container:release web -a yourproyect
```


