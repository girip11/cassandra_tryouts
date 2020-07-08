# Cassandra tryouts

Examples and tryouts of Apache Cassandra based on the Datastax workshop

## Setting up cassandra locally using docker compose

* [Docker compose setup for datastax cassandra](https://medium.com/@jscarp/quick-dev-setup-of-datastax-enterprise-3212e1813821)
* [Running datastax data studio](https://medium.com/@michaeljpr/five-minute-guide-getting-started-with-cassandra-on-docker-4ef69c710d84)

```Bash
# If you need graph services, use docker-compose-with-graph.yml
docker-compose -f docker-compose.yml up
```

## Setting data stuio

* Launch **<http://localhost:9091>** and upload the notebooks in the **notebooks** directory.

* In the studio connections change the host/ip from 127.0.0.1 to dse(Cassandra container/service name)

---

## References

* [Workshop Github repo](https://github.com/DataStax-Academy/cassandra-workshop-series)
* [Datastax Cassandra docker setup](https://github.com/jeffreyscarpenter/dse-docker-project-template)
