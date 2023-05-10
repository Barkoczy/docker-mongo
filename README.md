# Docker mongo server

Example for mongo server via docker

## Make .env file

```shell
cp .env.example .env
```

## Edit .env file (vim, nano.. your favorite choice)

Open enviroment file

```shell
vim .env
```

Edit default enviroment file if u need

```shell
MONGODB_ROOT_PASSWORD=password
MONGODB_ENABLE_JOURNAL=true
MONGODB_ENABLE_DIRECTORY_PER_DB=yes
MONGODB_SYSTEM_LOG_VERBOSITY=3
MONGODB_EXTRA_FLAGS=--wiredTigerCacheSizeGB=2
```

## Run

```shell
docker-compose up -d
```

## Down

```shell
docker-compose down
```

## Check

```shell
docker-compose ps
```
