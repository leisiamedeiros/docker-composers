# What is [Elastic](https://www.elastic.co/) and [Kibana]( https://www.elastic.co/what-is/kibana) ?

- Elasticsearch is a distributed RESTful data search and analysis engine capable of serving a growing number of use cases.
- Kibana is a free and open user interface for you to view your Elasticsearch data and browse the Elastic Stack.

# How can I start?

Jus execute the command bellow to run the containers.

```bash
$ docker-compose -f "ElasticKibana/ek-docker-compose.yml" up -d
```

# Done!

Now you can access the default host:port `http://localhost:5601/` to access the dashboard.

# Dev Tools

You can use the dev [tools](https://www.elastic.co/guide/en/kibana/7.14/console-kibana.html) to query using [Kibana Query Language](https://www.elastic.co/guide/en/kibana/7.14/kuery-query.html)

Examples:

- List
```curl
GET _cat/indices
```

- Search
```curl
GET indexname/_search

GET _search
{
  "query": {
    "match": {
      "_index": "indexname"
    }
  }
}
```

- Search for `_id`
 ```curl
GET indexname/_doc/id
```
