docker run -d --name mongodb-server -p 27017:27017 mongo:lastest
docker exec -it a9b24b1deebd mongosh

show dbs;
use testdb;
show collections;
db.users.find();

db.users.find({"lastName" : Polimetla})

db.user.find({ _id: ObjectId('670419ca640370613bc8819c')})