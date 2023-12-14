# connect to container
docker-compose exec mongodb bash

# connect with mongosh
mongosh "mongodb://root:*****@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://fabio:*****@mongo-db-cluster-test-1.rdzo938.mongodb.net/"

# commands
show dbs
show collections
