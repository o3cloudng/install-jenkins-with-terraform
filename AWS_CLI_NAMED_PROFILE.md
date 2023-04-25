# NAMED PROFILE

* aws cli on your system
* Create an IAM user with programmatic access on AWS
* Use the User credentials to create a profile


## Install AWS CLI [HERE](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

Download the file for your operating system and install

To confirm aws cli installation?

``` aws --version ```

## Create IAM user from AWS console

IAM > Users > Add user > name_of_user > programmatic_access > Add Admin policy 

``` terraform-user ```

Get 
ACCESS_KEY_ID
ACCESS_SECRET_KEY


## TO Create A Profile
```
aws configure --profile <terraform-user>
```

Then supply the following details
```
AWS_ACCESS_KEY_ID=
AWS_ACCESS_SECRET_KEY=
DEFAULT_REGION=<us-east-1>
Defaul Output Format = 
```

