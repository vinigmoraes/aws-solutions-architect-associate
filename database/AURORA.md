# AWS Aurora

![amazon_aurora](https://github.com/vinigmoraes/aws-solutions-architect-associate/assets/11817331/ddeed2f8-934c-47ff-a6da-e6e6c294c147)

It's a Cluster of Global Scale Relational Database managed and available by AWS, it's provide up to 128T of storage double of RDS (64T) and has 30% more performance than RDS.

Aurora support two engines *PostgreSQL* and *MySQL*

## Replica

Aurora can provide up to 15 replicas of read multi AZ or Cross Region, when a replica is created Aurora enable a endpoint to consume replica data however consuming a replica data has the possibility of **eventual consistency** duo to replication factor, to avoid this situation consider to consume the endpoint of master in the cluster.

## 

## Advantages
- High Availability & Disaster Recovery
- More perfomance than RDS
- More replicas than RDS (7)
- Integrated with AWS Services (SQS, Lambda & more)

## Desavantages
- 20% more expensive than RDS (ACP x VCP)
- Only two engines supported
- Vendor Lock (Available only in AWS)

## Extra Content

- [How Ze Delivery used Aurora](https://www.hipsters.tech/python-graphql-e-serverless-no-ze-delivery-hipsters-on-the-road-53/)