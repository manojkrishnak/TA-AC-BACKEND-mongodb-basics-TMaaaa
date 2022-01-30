writeCode

Write code to:-

- create a database named `mountains`
use mountains
- a collection inside that database named `himalayas`
db.createCollection("himalayas")
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`
db.himalayas.insert({name: 'Dhauldhar range', height: '4000 mtrs'})
- insert multiple document using insertMany command
db.himalayas.insert([{name: 'Dhauldhar range', height: '4000 mtrs'}, {name: 'Dhauldhar range-1', height: '4000 mtrs'}, {name: 'Dhauldhar range-3', height: '4000 mtrs'}])

- find all documents from mountains
db.himalayas.find({})
- find a single document using name
db.himalayas.findOne({name: "Dhauldhar range"})
