# Øvelse: Enviroment Variables

I har tidligere gjort brug af enviroment variabler i forhold til deployment på Herokus server

````    
  server.listen(process.env.PORT || 3003);
````   

På heroku under **settings** kan i skrive jeres egne variabler ind.

![](https://github.com/ElectiveNodejs/09_REST_api/blob/master/img/Screen%20Shot%202017-11-02%20at%2016.28.41.png)

## Øvelse
Tilret den applikation i lavede sidst med forbindelse til MongoDb databasen, så at i har url, username og password liggende som enviroment variabler i stedet for hard coded i selve applikationen som her:

````    
const mongodburl = 'mongodb://clbo:1234@cluster0-shard-00-00-9zvke.mongodb.net:27017,cluster0-shard-00-01-9zvke.mongodb.net:27017,cluster0-shard-00-02-9zvke.mongodb.net:27017/zalandodummy?ssl=true&replicaSet=Cluster0-shard-0&authSource=admin';
````     




