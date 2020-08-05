#Charizard "opensooq"
....
docker-compose -f docker-compose.1.yml -f docker-compose.2.yml  -f docker-compose.cnf.yml -f docker-compose.shard.yml up

docker-compose -f docker-compose.1.yml -f docker-compose.2.yml  -f docker-compose.cnf.yml -f docker-compose.shard.yml logs -f

...
