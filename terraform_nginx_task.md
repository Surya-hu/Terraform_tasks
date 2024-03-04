### create 2 EC2 instance on 2 different regions and install nginx using terraform script

Created Directory called inginx_terra and created below files with the contents as shown in the picture  
Main.tf  
userdata.sh  
chmod +x uerdata.sh  

main.tf
![image](https://github.com/Surya-hu/Terraform_tasks/assets/119995742/e69ae72b-39fe-42ea-9ce4-7e9d69e06bec)

userdata.sh
![image](https://github.com/Surya-hu/Terraform_tasks/assets/119995742/dafd32ad-2108-4030-ade1-a0b14c03df5d)

After creating terraform file and bash script to install nginx.
ran below commands  
`terraform init`  
`terraform plan`  
`terraform apply`  
then verified if the EC2 machines created in respective regions and tried to access it using public IP and found working. Hence the task completed succesfully.  

![image](https://github.com/Surya-hu/Terraform_tasks/assets/119995742/321513c0-1080-48ff-bfac-0f60c494cb1f)

![image](https://github.com/Surya-hu/Terraform_tasks/assets/119995742/18057e6d-0517-4ea0-89c0-25cede0b0de2)

![image](https://github.com/Surya-hu/Terraform_tasks/assets/119995742/57251c09-83c0-4d3d-a9f1-015301ad683a)

![image](https://github.com/Surya-hu/Terraform_tasks/assets/119995742/f79040af-cbaf-4e56-974c-e6b4c35a44af)

