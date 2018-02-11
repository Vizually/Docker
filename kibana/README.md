# Kibana Docker Compose config

This Docker Compose configuration features OSS versions of Elasticsearch and Kibana.

Metricbeat is also included, which will collect system data and automatically create indices and sample dashboards in Kibana.

## Run

All you need is run `docker-compose up` from the directory of the version you'd like to run.

For instance:

```
cd kibana/6.2
docker-compose up
```

Two services are now available through an exposed port:

* **Elasticsearch**: http://localhost:9200
* **Kibana**: http://localhost:5601

