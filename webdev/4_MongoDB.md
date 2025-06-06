🟢 Easy Level Questions
1. What is MongoDB?
```
MongoDB is a NoSQL, document-oriented database used for high volume data storage. It stores data in JSON-like BSON format.
```

2. What is a collection in MongoDB?
```
A collection is a group of MongoDB documents, similar to a table in relational databases.
```

3. What is a document in MongoDB?
```
A document is a record in MongoDB, stored as a BSON (binary JSON) object.
```

4. Is MongoDB schema-less?
```
Yes, MongoDB is schema-less, meaning each document in a collection can have a different structure.
```
5. How do you insert a document in MongoDB?
```
Using the insertOne() or insertMany() methods.
```
6. How do you retrieve all documents from a collection?
```
Use db.collection.find() without any query parameters.
```
🟡 Intermediate Level Questions
7. What is the use of the _id field?
```
_id is a unique identifier for each document in a collection. It’s automatically generated if not provided.
```

8. What are indexes in MongoDB?
```
Indexes improve the performance of search queries by allowing MongoDB to search documents faster.
```

9. What is aggregation in MongoDB?
```
Aggregation is a way of processing data records and returning computed results, similar to GROUP BY in SQL.
```

10. Explain the difference between find() and findOne().
```
find() returns a cursor for multiple documents; findOne() returns the first matching document.
```

11. How can you update a document?
```
Use updateOne(), updateMany(), or replaceOne() methods.
```

12. What is the difference between embedded and referenced documents?
```
Embedded documents are nested within a document; referenced documents use a foreign key to reference another document.
```

🔴 Hard/Advanced Level Questions
13. What is a replica set in MongoDB?
```
A replica set is a group of MongoDB servers that maintain the same data set, providing redundancy and high availability.
```

14. What is sharding in MongoDB?
```
Sharding is a method for distributing data across multiple machines to support horizontal scaling.
```

15. What is a capped collection?
```
A capped collection is a fixed-size collection that automatically overwrites the oldest documents when it reaches its size limit.
```

16. How does MongoDB ensure data consistency?
```
MongoDB uses write concerns and read preferences to manage consistency levels.
```

17. What is the Aggregation Pipeline?
```
It’s a framework that allows documents to pass through multiple stages like $match, $group, $sort to transform and analyze data.
```

18. How does MongoDB handle transactions?
```
MongoDB supports multi-document ACID transactions starting from version 4.0.
```

19. How do you perform a text search in MongoDB?
```
Create a text index on fields and use the $text operator to search.
```

20. What is the difference between MongoDB and traditional RDBMS?
```
MongoDB is schema-less, uses documents, and scales horizontally; RDBMS uses fixed schemas, tables, and scales vertically.
```

