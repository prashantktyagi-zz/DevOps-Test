# Pre-requisite

install ansible on Linux Distro

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
aws
```


# Run playbook

```bash
ansible-playbook -i ec2.py site.yml
aws

ISSUE:

https://docs.aws.amazon.com/AmazonS3/latest/dev/RESTAuthentication.html#RESTAuthenticationTimeStamp
