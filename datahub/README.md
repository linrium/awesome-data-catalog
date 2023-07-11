This docker image is using Elasticsearch instead of Neo4j for graph to reduce complexity. You can check the document
for more information.

## Steps:
1. docker-compose up -d
2. go to http://localhost:9002/
3. username = datahub and password = datahub

## Run by CLI
Install CLI
```shell
python3 -m pip install --upgrade pip wheel setuptools
python3 -m pip install --upgrade acryl-datahub
datahub version
```

Start docker
```shell
datahub docker quickstart
```

Ingest data for testing
```shell
datahub docker ingest-sample-data
```

## Examples:
- Other docker files: https://github.com/datahub-project/datahub/tree/master/docker
