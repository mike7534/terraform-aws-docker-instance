```hcl

provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "mike7534/docker-instance/aws"
    key_name = "clarusway"
}