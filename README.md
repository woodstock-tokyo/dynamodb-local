# DynamoDB Local

Docker-compose for dynamodb-local

## Spin up

```bash
docker-compose up
```

## Volume set up

```bash
mkdir -p ./docker/dynamodb
sudo chmod 777 ./docker/dynamodb
```

## dynamodb admin

```bash
npm i -g dynamodb-admin
set DYNAMO_ENDPOINT=http://localhost:8000
```

### start dynamodb admin

```bash
dynamodb-admin
```

Then access `localhost:8001`
