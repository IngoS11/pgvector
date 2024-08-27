# Postgres as a Vector Database

Demo Postgres Server with Vector addon. After clone copy .env.template to .env and replace
configuration with your own information. Then use docker-compose to start the containers
```
>> docker-compse up -d
```
Access [PGAdmin](http://localhost:5016) and use the username and password you configured.
Register a new server in PGAdmin using the following details:
```
Host name/address: pgvector_db
Port: 5432
Username: The value of POSTGRES_USER from the .env file.
Password: The value of POSTGRES_PASSWORD from the .env file.
```

## Link to Article
https://www.bitdoze.com/deploy-pgvector-pgadmin-docker/
