# Open Search docker

## Usage

Start the docker compose file with detached mode:

```bash
docker compose up -d
```

You can check the Open Search running at:

```bash
> curl localhost:9200
{
  "name" : "5c74ea3e97b7",
  "cluster_name" : "docker-cluster",
  "cluster_uuid" : "JITMxla_TUekSXTvubB7RQ",
  "version" : {
    "distribution" : "opensearch",
    "number" : "2.11.0",
    "build_type" : "tar",
    "build_hash" : "4dcad6dd1fd45b6bd91f041a041829c8687278fa",
    "build_date" : "2023-10-13T02:56:10.311811371Z",
    "build_snapshot" : false,
    "lucene_version" : "9.7.0",
    "minimum_wire_compatibility_version" : "7.10.0",
    "minimum_index_compatibility_version" : "7.0.0"
  },
  "tagline" : "The OpenSearch Project: https://opensearch.org/"
}
```

And access the Dashboard at [http://localhost:5601/](http://localhost:5601/)