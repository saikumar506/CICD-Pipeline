# CICD-Pipeline
## To install jenkins provide permissions to intall
```
sudo chmod 777 jenkins.sh
```
## Execute the script file
```
sh jenkins.sh
```
### Jenkins uses Port 8080, so after installation, you must go to your AWS EC2 Security Group and open Inbound Port 8080.
## Copy the public IP
```
<publicip>:8080
```
## To unlock jenkins copy the password from the server and paste it in browser
```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```

