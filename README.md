# Ojdbc-redis

This will be a Java library built on top of Oracle JDBC Driver (OJDBC), Universal Connection Pooling (UCP), Oracle Notification Service (ONS), Reactive
Streams Ingestion Library (RSI), Oracle Public Key Infrastructure Library (ORAPKI) and Oracle Security Developer Tools (OSDT_
CERT and OSDT
_CORE).
This library has three main objectives:
Register as a Connector/Trigger with the Redis Cluster to execute the Write-Behind and Read-Through (using Redis Gears).
Execute the Object-Relational Mapping from Redis to Oracle Database (using Hibernate).
Leverage all the complexity associated with the configuration of the Oracle libraries mentioned above to exploit those features transparently:
Runtime connection load balancing (for RAC Databases).
Fast Connection Failover.
Transaction Affinity.
Asynchronous execution (with JDBC Async Extensions).
Pipelining (with JDBC pipelining in 23c).
Efficient pooling (with UCP).
Streaming capabilities and best performance for loading with Direct Path (with Reactive Stream Ingestion Library).
Data changes notification with Continuous Query Notification Service.
