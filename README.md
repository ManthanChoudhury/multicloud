# HYBRID MULTI CLOUD


![aws](https://user-images.githubusercontent.com/45136716/84601077-696aeb00-ae9b-11ea-9954-26b70ba4ff1b.jpg)



Have to create/launch Application using Terraform
1. Create the key and security group which allow the port 80.
2. Launch EC2 instance.
3. In this EC2 instance use the key and security group which we have created in
step 1.
4. Launch one Volume (EBS) and mount that volume into /var/www/html
5. Developer have uploded the code into github repo also the repo has some
images.
6. Copy the github repo code into /var/www/html
7. Create S3 bucket, and copy/deploy the images from github repo into the s3
bucket and change the permission to public readable.
8 Create a Cloudfront using s3 bucket(which contains images) and use the
Cloudfront URL to update in code in /var/www/html.

<h1> Using Terraform(automating tool) </h1>


1. copy file auto.tf

2. start typing.
         
       terraform init
       
       terraform validate
       
       terraform apply -auto-approve
       
 3. It will start performing task according to coded file.
 
 ![Screenshot (17)](https://user-images.githubusercontent.com/45136716/84601575-d5028780-ae9e-11ea-999b-c5781c803885.png)
![Screenshot (18)](https://user-images.githubusercontent.com/45136716/84601577-d8960e80-ae9e-11ea-83de-7f1a00096776.png)
![Screenshot (19)](https://user-images.githubusercontent.com/45136716/84601578-daf86880-ae9e-11ea-8451-c587b121d8f2.png)
.
.
.
![Screenshot (22)](https://user-images.githubusercontent.com/45136716/84601581-e055b300-ae9e-11ea-8074-da4a347c0f6c.png)     



    
READY CLOUD PAGE



![Screenshot (15)](https://user-images.githubusercontent.com/45136716/84601112-a1722e00-ae9b-11ea-8646-ebfa99167f37.png)



![Screenshot (16)](https://user-images.githubusercontent.com/45136716/84601116-a8993c00-ae9b-11ea-881b-d30d445c56f0.png)


4. to destory entire enviroment.

       terraform destroy -auto-approve


 ![Screenshot (29)](https://user-images.githubusercontent.com/45136716/84601871-0f6d2400-aea1-11ea-9abf-a3423b84c799.png)
![Screenshot (30)](https://user-images.githubusercontent.com/45136716/84601874-11cf7e00-aea1-11ea-8fce-c048d3857765.png)
![Screenshot (32)](https://user-images.githubusercontent.com/45136716/84601878-15630500-aea1-11ea-982f-c751f84f9785.png)


