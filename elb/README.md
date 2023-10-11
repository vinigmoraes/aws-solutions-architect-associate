# Elastic Load Balancer

## Why use load balancer ?

- Spread Load across multiple instances
- Expose a single point of access (DNS)
- Handle Failures of down instances (redirect)
- Health Check (not send request to a unhealty instance)

Can be Integrated with:

- EC2
- ECS (Containers)
- Lambda Functions

## Application Load Balancer

Not so fast as NLB but is more friendly and has more features

Uses HTTP / HTTPS protocol in requests

## Network Load Balancer

Provide the hightest performance and lowest latency

Uses TCP / TCL protocol in requests

## Target Group

A group of instances to be attached to ELB where ELB will redirect the requests

## AutoScaling Group

Manage the load of servers in Cloud, ensuring that have minimum and maximum of instances

*Scale Out*

Increase the number of instances

*Scale In*

Decrease the number of instances

*Policies*

Can set scale configuration for ASG:

- CPU Utilization
- Average Network In / Out
- Memory Utilization
- Custom Metrics

## CloudWatch Metrics

CloudWatch collected can then be used to set up alarms, send notifications, and trigger actions
