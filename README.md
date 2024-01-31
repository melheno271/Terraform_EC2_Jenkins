# Fully functional Jenkins server on EC2 (Amazon Linux AMI) instance

* You need to create a key "jenkins-server-key"
* You need to modify backend information

1. Terraform init
2. Terraform plan
3. Terraform apply -auto-approve

After few minutes the jenkins server will be deployed.
public_ip address will be displayed.
In order to connect to Jenkins Server you can access port 8080 of the public ip. 
