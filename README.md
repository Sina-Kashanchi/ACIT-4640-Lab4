# 4640-w4-lab-start-w25


## Command to generate a new key pair:
`ssh-keygen -t rsa -b 4096 -f ~/.ssh/lab_4 -C "your-email@example.com"`

## Steps to connect to the instance:
1. Go to the folder where the Terraform configuration file is stored.
2. Run the command `terraform init`.
3. Run the command `terraform apply`.
4. Type **yes** to let Terraform perform actions described in the configuration file.
5. Ssh into the instance using the dns_name or public_ip shown as the output.

