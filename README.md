# terraform-aws-vpc

You can use it with config:
```
module "vpc" {
  source  = "MarkPage2k1/vpc/aws"
  version = "1.0.0"

  vpc_cidr_block    = "10.0.0.0/16"
  private_subnet    = ["10.0.1.0/24", "10.0.2.0/24", "10.0.3.0/24"]
  public_subnet     = ["10.0.4.0/24", "10.0.5.0/24", "10.0.6.0/24"]
  availability_zone = ["ap-southeast-1a", "ap-southeast-1b", "ap-southeast-1c"]
}
```
