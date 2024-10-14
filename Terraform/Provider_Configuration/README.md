
# Provider Authentication and Configuration

 Note : Here the provider is AWS Cloud service
## Login to the AWS console
  Search for IAM
  
## **IAM** 
-> User -> Create user

## **Specify user details** 
-> User name -> Provide user access to the AWS Management Console

## **Set permissions**
-> Permissions options -> Attach policies directly

-> Permissions policies -> AmazonEC2FullAccess

-> create user

-> Return to users list

 ## Click on the user name
 
 # **User-Name**       
-> Security Credentials -> Access keys -> Create access keys 

# **Access key best practices & alternatives**
-> Command Line Interface (CLI) 

# **Retrieve access keys **

### **Access key**
 Access key                Secret access key
       
 ````````                   `````````````````
 AKIAYDL7PISCKECF5REE        ***************
 ``````````                  ````````````````````` 



 


# Now export the AWS Keys into Env. Variables

``````````````````````
echo "export AWS_ACCESS_KEY_ID="my-access-key" " >> ~/.bashrc
```````````````````````

```````````````````````````````````````````````````````````````````````````````
echo "export AWS_SECRET_ACCESS_KEY="my-secret-access-key" " >>  ~/.bashrc
``````````````````````````````````````````````````````````````````````````
```````````
source ~/.bashrc
`````````````

``````````````````````
set | grep -i AWS
``````````````````````````
