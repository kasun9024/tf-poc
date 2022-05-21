# tf-poc
create web server on ec2 instance
1. Create VPC
2. Create internet gateway 
3. Create custom route table
4. Create subnet 
5. Associate subnet with route table
6. Create a security group open ports 80,443,22
7. Create network interface for subnet-1
8. Attach public ip useing depends_on attribute to mention depends on IGW
9. Create ubuntu server install/enable apache
