# End to End CI/CD Project with AWS

### **Complete Architecture**
![Image](architecture.png)

### **Set up an IAM user:**
- It is a best practice to work with IAM user instead of working through Root user.
 ![Image](1.0-framed.png)
- Attach ***AdministratorAccess*** policy to the IAM user
- Now the work is only with IAM User, I am not going to work in Root user

### **Launch an EC2 Instance:***
![Image](1.0-framed.png)
- Give name to EC2 instance.
- Select AmazonAMI
- create-key pair
- save it in your PC
- Don't forget to change network access to MyIP in the Network settings.
- Click on create instance.

