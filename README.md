# Cassandra

## Keyspace, Table, Data Creation

check 
- table.sql
- [tutorialspoint](https://www.tutorialspoint.com/cassandra/cassandra_create_data.htm)
- [Apache Cassandra](https://cassandra.apache.org/doc/latest/cql/index.html)
- [datastax](https://docs.datastax.com/en/cql-oss/3.3/cql/cql_reference/cqlCreateKeyspace.html)

## Kubernetes

check following things before applying

- storageclass
- service IP


## Cassandra Best Practices

[hardware requirement](https://cassandra.apache.org/doc/latest/operating/hardware.html)
- Minimal production
  - 2 core
  - 8 GB memory
- HEAP_NEWSIZE should be 25% of MAX_HEAP_SIZE

## Operation

default superuser role 'cassandra'