<!--StartFragment-->

**Goals for this lab:**

*   Configure your account on the AWS Canvas site
*   Use the AWS Academy Terminal
*   Use the AWS Academy Console
*   Launch an EC2 Instance
*   Use SSH to access EC2 Instance
  
<!--StartFragment-->
First we need to navgate to navigated through the "**AWS Academy Cloud Foundations**" by going to the "**Modules**" and clicking on the "**Sandbox Environment**", As it shown below:
<!--EndFragment-->

![task_1.png](./Images/task_1.png)

<!--StartFragment-->
Within the sandbox, we need to start the lab by clicking on "**Start Lab**,"
<!--EndFragment-->
![2.png](./Images/2.png)
<!--StartFragment-->
Output of " aws sts get-caller-identity" from AWS terminal (command prompt within lab)
<!--EndFragment-->
![3.png](./Images/3.png)
<!--StartFragment-->
Now we need to check the state of instance and make suer it is running, we need to follow the following steps as shown in the screenshots below:
<!--EndFragment-->
![4.png](./Images/4.png)![5.png](./Images/5.png)![6.png](./Images/6.png)

##SSH access through powershell
<!--StartFragment-->
In order to ssh to it we need a .pem file, to get the .pem file we need to do the following:
In the lab page go to "**Details**" > "**AWS**" > "**Show**":
<!--EndFragment-->
![7.png](./Images/7.png)


As we see below we are able to ssh to it using the following .pem file and the following commadn `ssh -i labsuser.pem ec2-user@3.235.169.29`
![8.png](./Images/8.png)























