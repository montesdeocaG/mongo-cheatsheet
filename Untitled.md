
# Mongo Db cheatsheet


Mongo is a general purpose distribuited cloud or local database, you can create your own cluster and connect to it.

## Operators


`$gte` greather than or equal\
`$gt` greather than  
`$lte` less than or equal
`$lt` less than
`$ne` not equal to

## Navigation

`mongo` start shell from cmd.
`show dbs` show list of stored databases.   
`use` works like windows cd, use selected db.  
`.createCollection()` create a collection inside the object db.  
`.pretty()` optional formatting for json indentation

## Insertion and removal 

`.collection.insert({key: val})` Insert a document in the collection  
`.collection.remove({key: val})` Removes the document if the expression is matched.  

## Find

`.collection.find()` shows documents inside the collection, can pass in an argument for the documents that match it.    
`.collection.find().count()` counts the number of matching documents  
`.collection.find().sort().` sorts based on arg {arg:int} int being 0 or 1 for descending |and ascending   


```python
## Aggregation
```

`.collection.aggregate({"$group": {"$-id":$val}})` group the selected data denoted by id  with the value specified as a parameter.


```python

```
