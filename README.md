# Running Falcons Project

### Running Docker

```
docker-compose up -d
```

### Duplicate .ENV.EXAMPLE

Duplique o arquivo .env.example renomeando para .env

### Install Dependencies

```
docker-compose exec falcons_app composer install
```

### Generate Key

```
docker-compose exec falcons_app php artisan key:generate
```

### Run NPM

```
npm install
```

### Run NPM Dev

```
npm run dev
```

### Rodando Migrations

```
docker-compose exec falcons_app php artisan migrate
```

### Configuring PostGres

Acesse o projeto em http://localhost

### Configuring PostGres

Acessar PGAdmin

http://localhost:16543

```
user: admin@admin.com.br
password: admin
```

Adicione um novo server

```
host: falcons_postgres
port: 5432
user: postgres
password: falcons
```
