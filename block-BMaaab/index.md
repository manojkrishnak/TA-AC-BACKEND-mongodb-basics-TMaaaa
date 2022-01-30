writeCode

Run these shell commands in mongo shell:

- db.version()
[//]: # 5.05
- db.stats()
[//]: # {
        "db" : "myFirstDb",
        "collections" : 1,
        "views" : 0,
        "objects" : 1,
        "avgObjSize" : 51,
        "dataSize" : 51,
        "storageSize" : 20480,
        "freeStorageSize" : 0,
        "indexes" : 1,
        "indexSize" : 20480,
        "indexFreeStorageSize" : 0,
        "totalSize" : 40960,
        "totalFreeStorageSize" : 0,
        "scaleFactor" : 1,
        "fsUsedSize" : 83092258816,
        "fsTotalSize" : 254721126400,
        "ok" : 1
}
- db.help()

Write code to

- create a database of your country name.
show india
- check list of databases to see newly created database.
show dbs
- check which database you are currently connected to ?
db
