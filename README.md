# AWS Short Notes


## Cloud Types

1. **Public Cloud**: AWS, Azure
2. **Private Cloud**: Common in banks, government systems, and internal enterprise environments
3. **Hybrid Cloud**: A combination of public and private cloud infrastructure

## Cloud Service Models

1. **IaaS (Infrastructure as a Service)**: EC2
2. **PaaS (Platform as a Service)**: Google App Engine, Render
3. **SaaS (Software as a Service)**: Google Drive, Dropbox, web-based software tools
4. **STaaS (Storage as a Service)**: AWS S3

# Regions and Availability Zones

- **Region**: Examples include Singapore, Seoul, Jakarta
- **Availability Zones**: A region contains multiple zones
- Example: Singapore has 3 Availability Zones

# EC2 Basics

- **VPC**: Virtual Private Cloud
- Connection flow:

```text
Client -> SSH (remote access) -> Security Group -> Server
```

# Key Pair
 Use Putty.
- **Private key**: Downloaded as a `.pem` file from ec2 
- **Public key**: Stored by AWS and placed on the EC2 instance
- **PuTTY access flow**: Public IP -> PuTTY -> `.ppk` credential


# Apache Server

Useful commands for installing and managing Apache (`httpd`) on Amazon Linux:

```bash
sudo su
cat /etc/os-release
yum install httpd
systemctl start httpd
systemctl status httpd
cd /var/www/html
ls
vim index.html
systemctl restart httpd
```

`httpd` is the Apache HTTP Server package.


## Specific Contents

- [Key Pair](./KeyPair.md)
- [CIDR](./CIDR.md)
- [Agent Forwarding](./Agent-Forwarding.md)


