Scenario
==============

#####New AWS Windows Server 2012
- Logged in as a local admin 

#####Aim

######Write a powershell script to complete the following:

- Add a local administrator user
- Rename the server - JE-AWS-TEST
- Add the server to the domain
- Tag AWS resources with “Env” value “Test”
- Fix an ip address of the server to 10.10.1.2
- Install Anti-virus - antivirus.msi
- Alert when complete - your choice...

######Resources
- S3 Bucket “setup-files”
- AccessKey accesskey1
- SecretKey secretkey1
- Region eu-west-1  
- Domain user “domainAdmin”
- Domain user Password “P@ssw0rd1234”
- Domain controller FQDN “DC.aws.test”
- DNS Server “DC.aws.test”
- DNS IP “10.10.1.1”
