provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "omerdogan16/docker-instance/aws"
    key_name = "firstkey"
}