# Pre-requisite

Install ansible on Linux Distro

```bash
sudo yum install ansible
```

install boto, boto3

```bash
sudo pip install boto boto3
```
Set aws credentails

```bash
touch ~/.aws/credentails
[default]
aws_access_key_id = <your_access_key_here>
aws_secret_access_key = <your_secret_key_here>

```
For more info: http://boto.readthedocs.io/en/latest/boto_config_tut.html


# Run playbook

```bash
ansible-playbook -i ec2.py site.yml
aws

ISSUE FACED:

https://docs.aws.amazon.com/AmazonS3/latest/dev/RESTAuthentication.html#RESTAuthenticationTimeStamp
