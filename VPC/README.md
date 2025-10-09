# VPC Peering

Here i have created two VPC bwtween different reason and peer them. Then test the communication between instances in each VPC.

## Architecture

| VPC A (10.0.0.0/16)  ↔    | VPC Peering Connection  ↔ | VPC B (172.31.0.0/16       |
│ :-----------------------  | :------------------------ | :------------------------  |             | Subnet A (10.0.1.0/24)    |                           | Subnet B (172.31.1.0/24)   |
| :-----------------------  | :------------------------ | :------------------------  |
| EC2 Instance A (10.0.1.x) |                           | EC2 Instance B (172.31.1.x)|
