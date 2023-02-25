# This will create a MySQL 5.7 instance using Docker Compose

## To Run:

Make sure you've got docker and docker compose installed and execute:

`docker compose -f docker-compose.mysql5.yml up -d`

## To Shutdown (this will NOT delete the data)

`docker compose -f docker-compose.mysql5.yml down`

## To Shutdown and CLEAR all mysql data

`docker compose -f docker-compose.mysql5.yml down -v`

_NOTES:_

- Data will be stored in `data` dir.
- Put any initial database or sql scripts on `initdb` dir.
