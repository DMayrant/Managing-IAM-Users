This project is centered around managing AWS Identity and Access Management (IAM) users and roles using Terraform and YAML. 
IAM is one of the 4 pillars in cloud security and it important to follow the principle of least privilege by giving users and groups just the right amount 
access the AWS ecosystem to carry out specific task. The primary objective is to automate the process of creating users, assigning roles, and ensuring secure
role assignment. User information, including username and roles will be stored in a YAML file, while role information will be managed in Terraform. 
An important aspect of this project is to ensure that roles can only be assumed by the users assigned to them, adding an extra layer of security. 
