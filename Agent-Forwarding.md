# Agent Forwarding / Jump Box

- **Public subnet**: Used to access resources from outside
- **Private subnet**: Used for sensitive systems and internal services

## Basic Steps

1. Create subnets:
   - `172.31.0.0/20` -> 4096 total IPs
   - `172.31.16.0/20` -> 4096 total IPs
   - `172.31.32.0/20` -> 4096 total IPs
   - `172.31.48.0/20` -> 4096 total IPs (new private subnet)
2. Create a route table and associate it with the private subnet:
   - Route table name: `Private_Route`
   - Subnet association: `172.31.48.0/20`
3. Create 2 instances
