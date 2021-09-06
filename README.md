# elasticsearch-docker-dev-boilerplate
## healthCheck
- Cluster
```sh
$ curl -X GET "localhost:9200/_cat/health?v&pretty"
```

- Nodes
```sh
$ curl -X GET "localhost:9200/_cat/nodes?v&pretty"
```
