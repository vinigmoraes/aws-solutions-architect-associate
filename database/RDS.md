# Relational Database

Provide the possibility to create a relational database managed by AWS, multi AZ with scaling capability.

## Supported Engines

- MySQL
- PostgreSQL
- MariaDB
- Orable BYOL
- SQL Server

## Storage

RDS storage capacity is up to 64T

## AutoScaling

RDS detect when it's running out of free storage and scale automatically, avoiding manual scaling.

## Read Replica

Provide up to 7 replicas AZ, Cross AZ or Cross Region, replication is async so reads are *eventually consistent*