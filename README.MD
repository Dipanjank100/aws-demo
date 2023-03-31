## Step-by-step instructions for AWS using the Mumbai region, based on the provided file :
---
---
*Step-1 :*
--
    Go to the AWS Management Console and select the Mumbai region from the dropdown menu in the top right corner.
*Step-2 :* 
 --   
    Click on the EC2 service to navigate to the EC2 Dashboard.
*Step-3 :*
--
     On the EC2 Dashboard, click the "Launch Instance" button to start the process of creating a new EC2 instance.
*Step-4 :*
 --   
     Choose an Amazon Machine Image (AMI) from the list of available options. An AMI is a pre-configured virtual machine image that contains all the software and settings needed to launch an instance. In this demo, the Amazon Linux 2 AMI is used.
*Step-5 :*
  --  
     Select the instance type you want to use. The instance type determines the virtual hardware configuration of the instance. In this demo, the t2.micro instance type is used.
*Step-6 :*
--
    Configure the instance details, such as the number of instances to launch and the VPC network to use. If you are unsure of what settings to use, you can leave the default values.
*Step-7 :*
--
    Configure the storage options for your instance. You can choose to use the default settings or customize the storage based on your needs.
*Step-8 :*
-
    Configure the security group for your instance. A security group acts as a virtual firewall that controls the traffic to and from your instance. In this demo, a new security group is created and the default SSH rule is added to allow SSH access to the instance.
*Step-9 :*
--
    Review the instance details and click "Launch" to start the instance.
*Step-10 :*
--
     Choose an existing key pair or create a new one. A key pair is used to securely connect to the instance over SSH.
*Step-11 :*
--
    Once the instance is launched, you can connect to it using SSH. The transcript provides instructions on how to connect to the instance using the command line.
*Step-12 :*
--
    Once you are done using the instance, you can terminate it to avoid incurring unnecessary charges. To terminate the instance, go to the EC2 Dashboard, select the instance, and click the "Terminate" button. Confirm the termination when prompted.