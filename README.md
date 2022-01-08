# flask-react-postgres-on-docker

useful commands:

get things running

docker-compose up -d --build


check database

docker exec -t <id> bash

psql -U dev demo_db
  
or
  
docker-compose exec db psql --username=dev --dbname=demo_db

psql> \l
  
psql> \c demo_db
  
psql> \dt
