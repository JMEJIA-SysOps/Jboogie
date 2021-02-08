# Jboogie

 provider "aws" {
 region = "us-east-1"
 access_key = "AKIAJL2SEKNGQ4PEKNSA"
 secret_key = "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"
}
resource "aws_instance" "WEBSERVER" {
 ami           = "ami-0742a572c2ce45ebf"
 instance_type = "t2.micro"
 }
