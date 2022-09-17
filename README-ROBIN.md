docker run \
-d \
--name docker_mongo_container \
-p 27017:27017 \
-e MONGO_INITDB_ROOT_USERNAME=docker_mongo_username \
-e MONGO_INITDB_ROOT_PASSWORD=docker_mongo_password \
mongo



BACKEND APP is node-express-mongodb

FRONTEND APP is react-hooks-crud-web-api

