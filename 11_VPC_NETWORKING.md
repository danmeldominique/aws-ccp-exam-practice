# Overview

 - **VPC:** Private cloud. Section of cloud that is restricted for your own, private use
 - **Subnets:** Tied to AZ, network partition of the VPC
 - **Internet Gateway:** VPC level, provide internet access
 - **NAT Gateway/ Instances:** Gives internet access to private networks
 - **NACL:** Stateless, subnet rules for inbound and outbound
 - **Security Group:** Statefull, operate at EC2 level
 - **Peering:** Connect two VPC. No overlapping IP ranges. Non transitive
 - **Endpoints:** Provide private access to AWS services within VPC
 - **Flow logs:** Netowrk traffic logs
 - **Site to Site VPN:** Between on premise DC and AWS
 - **Direct connect:** Direct private connection to AWS
 - **Transit Gateway:** Connet thousands of VPC and on premise networks together