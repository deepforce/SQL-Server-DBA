# SQL Server Replication

## What is replication?

**Publisher:** distribute the data

**Subsriber:** receive the data

## Types of replication

1. **Snapshot replication**

   Not real-time data, latency can be one day.

2. **Transactional replication**

   real-time data, distribute source level updates from publisher to subscribers

3. **Merge replication**

   keep publisher and subscribers in sync, both subs and pubs can distribute changes