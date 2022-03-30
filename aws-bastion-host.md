Copy ssh private ssh key to host (Amazon Linux Example)
Assumes you are using the keypair assigned to the instance
```text
scp -i <keyfilename>.pem <keyfilename>.pem ec2-user@54.158.224.190:~/
```
set correct rights on private key
```text
chmod 600 <keyfilename>.pem
```
use key to access internal hosts
```text
ssh -i <keyfielname>.pem <internal_ip>
```
