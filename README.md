
Required Commands

create "aws" key 
```bash 
ssh-keygen -f ~/.ssh/aws 
```
- -f to set file name and location

import aws key to aws 
```bash 
#access the repo folder 
cd intro-to-ansible-lab-files

#give permission to the script
chmod +x ./scripts/import_lab_key
chmod +x ./scripts/delete_lab_key

# run the import key script 
./scripts/import_lab_key ~/.ssh/aws.pub

# run the delete key script 
./scripts/delete_lab_key 
```

set up ec2(s) with terraform 
```bash 
cd intro-to-ansible-lab-files/terraform

#initialize the folder
terraform init 

# validate the script 
terraform validate 

# build the ec2(s)
terraform apply

# after done with the lab 
terraform destroy
```

ansible commands
``` bash 
cd intro-to-ansible-lab-files/ansible

#check the playbook syntax (after done editing)
ansible-playbook --syntax-check playbook.yml

# run the playbook 
ansible-playbook playbook.yml
```


Required Commands

create "aws" key 
```bash 
ssh-keygen -f ~/.ssh/aws 
```
- -f to set file name and location

import aws key to aws 
```bash 
#access the repo folder 
cd intro-to-ansible-lab-files

#give permission to the script
chmod +x ./scripts/import_lab_key
chmod +x ./scripts/delete_lab_key

# run the import key script 
./scripts/import_lab_key ~/.ssh/aws.pub

# run the delete key script 
./scripts/delete_lab_key ~/.ssh/aws.pub
```

set up ec2(s) with terraform 
```bash 
cd intro-to-ansible-lab-files/terraform

#initialize the folder
terraform init 

# validate the script 
terraform validate 

# build the ec2(s)
terraform apply

# after done with the lab 
terraform destroy
```

ansible commands
``` bash 
cd intro-to-ansible-lab-files/ansible

#check the playbook syntax (after done editing)
ansible-playbook --syntax-check playbook.yml

# run the playbook 
ansible-playbook playbook.yml
```

<img width="526" height="470" alt="Pasted image 20260217212240" src="https://github.com/user-attachments/assets/e5a41da8-ae42-4a7e-ac70-261da1142693" />
