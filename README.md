# postgresql-docker-compose
costumize my user

### 사용법 ###
`cp example.env .env`
PORT, USER, PASS, change

`docker-compsoe up -d`

`docker exec -it postgresql bash`

`psql -U <username> -d <dbname>`
