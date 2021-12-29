# Unomi Docker Compose
Apache Unomi™: The Open Source Customer Data Platform

More information about Unomi at here: https://unomi.apache.org/get-started.html

Docker Stack:
- ElasticSearch:7.4.2
- Unomi:1.5.7

# Running Unomi
Unomi requires ElasticSearch so it is recommended to run Unomi and ElasticSearch using docker-compose:
```
docker-compose up -d
```

# Environment variables

- **`UNOMI_ELASTICSEARCH_ADDRESSES`** - The IP address of hostname for ElasticSearch. Example: ```UNOMI_ELASTICSEARCH_ADDRESSES=elasticsearch:9200```
