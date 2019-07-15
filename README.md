# How to run this example

## Step 1: Install MongoDB

- install mongodb by using brew `brew install mongodb`
- create the db directory where MongoDB stores its database: `mkdir -p /data/db` (maybe you need to run with sudo)
- ```chown -R `id -un` /data/db``` (maybe you need to run with sudo)

## Step 2: Start MongoDb daemon

- `mongod`

## Step 3: Create database "appdb"

```text
mongo
> show databases
> use appdb
```

Notes: MongoDB creates a database only when data is inserted into it
