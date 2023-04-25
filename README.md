# INSTALL JENKINS WITH TERRAFORM


## Create a Bash Script to install Jenkins
```install_jenkins.sh```

## ec2.tf
* Set provider
* Created VPC
* Security group and Opened ports 80 & 22
* EC2 Instance
* AMI - Amazon linux 2

* ssh into the ec2 instance
* Copied install_jenkins.sh file into the server
* Make bash script file install_jenkins.sh excutable
* Ran the bash script file
* Ouput the DNS of the instance
