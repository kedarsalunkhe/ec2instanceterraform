# ec2instanceterraform

This is an simple ec2 instance been created using terraform
You need to configure aws cli as well as terraform on your machine
Excution steps for creating your first ec2 instance are:
You need to execute these steps from the directory in which the terraform file is located 
  1. terraform init <-- this will download the necessary provider plugins
  2. terraform plan <-- this command will show what your script will perform when executed also display if their are any error in the terraform file
  3. terraform apply <-- this will create the ec2 instance for you and you can check from the aws console if the ec2 instance been created or not.
