# Static Website on AWS S3 with Terraform

This project hosts my personal **portfolio website** (HTML/CSS) on **Amazon S3**, with all infrastructure managed using **Terraform**.

---

## Features
- Host static website on AWS S3  
- Terraform for Infrastructure as Code (IaC)  
- Custom error page (`error.html`)  
- Public access with bucket policy  
- Easy to deploy and destroy  

---

## Prerequisites
- [Terraform](https://developer.hashicorp.com/terraform/downloads) installed  
- [AWS CLI](https://docs.aws.amazon.com/cli/) configured (`aws configure`)  
- AWS account with permissions for S3  

---

## How to Deploy

1. **Clone the project**
   ```bash
   git clone https://github.com/edwarddume55/portfolio-s3-terraform.git
   cd portfolio-s3-terraform

2. **Initialize Terraform**
   ```bash
   terraform init


3. **Plan**
   ```bash
   terraform plan


4. **Apply**
   ```bash
   terraform apply -auto-approve

5. **Access Your Site**
   Terraform will output the S3 website endpoint

  e.g.  http://<bucket-name>.s3-website-<region>.amazonaws.com

   
6. **Destroy Infrastructure**
    
    terraform destroy -auto-approve

##  Contact

- 📩 [Email](mailto:edwarddume55@gmail.com)  
- 💼 [LinkedIn](https://www.linkedin.com/in/edward-dume)  
- 💻 [GitHub](https://github.com/edwarddume55)  

