# This my setup script configurations

[Tips]
MongoDB config - Replica Set
 1. remove the environment vars MONGO_INITDB_ROOT_USERNAME and MONGO_INITDB_ROOT_PASSWORD
 2. disable security authorization in the mongod.conf
 After those, just run rs.initiate() to intialize the replica set

