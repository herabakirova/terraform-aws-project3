# project-group-project-3
```hcl
module "group-project-3" {
        source = "herabakirova/project3/aws"
        version = "0.0.1"
        region = "us-east-2"
        vpc_name = "project"
        cidr = "10.0.0.0/16"
        subnet1_cidr = "10.0.1.0/24"
        subnet1_name = "subnet1"
        subnet2_cidr = "10.0.2.0/24"
        subnet2_name = "subnet2"
        subnet3_cidr = "10.0.3.0/24"
        subnet3_name = "subnet3"
        ig_name = "main"
        rt_cidr = "0.0.0.0/0"
    rt_name = "route"
    ec2_type = "t3.2xlarge"
    az = "us-east-2a"
    ec2_name = "project ohio"
}
```