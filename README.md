# to-do_app
This is a to-do app which demonstrates how to spin up a node.js app inside a docker container


Run `docker-compose up`

Run `docker exec -it <containerId> mysql -p todos` access to the db inside the container

Run app without the DB `node src/index.js` or `nodemon`