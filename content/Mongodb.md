---
tags:
  - mongodb
  - nosql
  - database
---
# MongoDB

MongoDB is a document-oriented NoSQL database that stores data as flexible JSON-like documents (BSON).

## Key concepts

- **Database** - A container for collections
- **Collection** - A group of documents (similar to a table)
- **Document** - A single record stored as BSON

## Example document

```json
{
  "_id": "64a1b2c3d4e5f6a7b8c9d0e1",
  "title": "MongoDB Basics",
  "tags": ["database", "nosql"],
  "author": {
    "name": "Alice",
    "email": "alice@example.com"
  }
}
```

## Query example

```javascript
db.articles.find({ tags: "nosql" }).sort({ title: 1 });
```

## Parent

- [[Nosql]]
