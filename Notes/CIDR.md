# CIDR

## CIDR (Classless Inter-Domain Routing)

- Before CIDR, Class A, B, and C networks had fixed sizes:
  - Class A: about 16.7 million IPs
  - Class B: 65,536 IPs
  - Class C: 256 IPs
- After CIDR, IP ranges can be allocated more flexibly:
  - Around 300 IPs -> `/23` -> 512 total addresses
  - Around 1000 IPs -> `/22` -> 1024 total addresses

## IPv4 CIDR Examples

- `172.31.0.0/16`
  - `32 - 16 = 16`
  - `2^16 = 65,536` IP addresses
- `0.0.0.0/0`
  - Open to all IP addresses on the internet
