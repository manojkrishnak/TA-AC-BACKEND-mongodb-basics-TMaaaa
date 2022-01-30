writeCode

Write command to

- List collections from a database.
show collections
- create a new collection in your country database which you created recently.

Write code to:-

- crate a database named `weather`
use weather
- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.
db.createCollection("temperature", {capped: true, size: 2048, max: 3})
A limit more than 3 will replace the older document created.
- create a simple collection named `humidity`
 db.createCollection("humidity")
- check whether `temperature` collection is capped or not ?
 db.temperature.stats()["capped"]
- Delete `humidity` collection and then the entire database(weather).
 db.humidity.drop()
  db.dropDatabase()