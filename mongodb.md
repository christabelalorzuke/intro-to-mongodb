#MongoDB Cheatsheet

Show the version of database server
```
   db.version()
```
Returns some statistics about MongoDB server
```
   db.stats()
```

List all the database in the MongoDB server
```
   show dbs
```
Switch to use the database specified
```
   use <dbName>
```   
Create new collection in the database
```
   db.create collections('name')
```
list all collections under the specified database
```
   show collections
```   