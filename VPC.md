# Virtual Private Cloud

## Knowledge to Learn

- VPC, Subnets, Internet GateWays & NAT Gateways
- Security Groups, Network ACL (NACL), VPC Flow Logs
- VPC Peering, VPC Endpoints
- Site to Site VPN & Direct Connect
- Transit Gateway



## IP Addresses in AWS

- IPv4: Internet Protocol version 4 (4.3 B Addresses)
  - Public IP: can be used on the internet.
  - Private IP: can be used on the private networks (LAN) such as internal AWS networking.
  - EC2 instance gets a new public IP every time you restart. However, it's private IP will will not change.

- IPv6: much more addresses.
  - Each IP is public



## VPC & Subnets Primer

- It's within the region.  But it could cross AZs.
- Subnets: part of VPC, to partition network inside the VPC
- A public subnet, have access to public internet. Subnets are within AZs.
- A private subnet: could place data base. It could access internet, but is not accessable from public internet.
- Route Table

## Internet Gateway & NAT Gateways

- I Gateway helps the VPC instances to connet with the internet
- NAT Gateways: NAT in a public subnet and a route from private subnet to pubic subnet.



## Network ACL & Secuirty Groups

NACL is a firewall controls traffic from and to subnet. (Subnet level)

Security group that controls traffic to and from an INI / An EC2 Instance. (Instance level)



## VPC Peering

- Connect two VPCs privately using AWS's network. Make them behave as if they were in the same network. Must not have oerlapping CIER.
- VPC peering is not transitive.

When peering with another account, need account ID.

