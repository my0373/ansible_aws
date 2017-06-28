# ansible_aws
AWS Test

Either pass the EC2 variables in to role, or specify them in the 
    
    roles/ansible_aws/defaults/main.yml


I run this with 

    ansible-playbook -i ./inventory --ask-vault-pass ./create_lab.yaml
    

Parameters required are

* access_key_id: 
* secret_access_key:
* aws_vpc_id: 
* aws_ami_id: 
* aws_subnet_id: 
* aws_availability_zone: 
* aws_keypair_name: 
* aws_security_group: 