# Relation Database Service - RDS

![RDS](images/rds.png)

## Description

Provide the possibility to create a relational database managed by AWS, multi AZ with scaling capability.

## Supported Engines

- MySQL
- PostgreSQL
- MariaDB
- Orable BYOL
- SQL Server

## Storage

RDS storage capacity is up to 64T

## Availability

Provide up 6 replicas between maximo of 3 regions (Cross Region), when usigin replication factor consequentily we have **eventually consistent data** on the read replicas.

## AutoScaling

RDS detect when it's running out of free storage and scale automatically, avoiding manual scaling.