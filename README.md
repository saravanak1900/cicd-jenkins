# cicd-jenkins
## Jenkins tutorial
### Install STABLE LTS Jenkins 
####################################

```
sudo -i
wget -O /etc/yum.repos.d/jenkins.repo  https://pkg.jenkins.io/redhat-stable/jenkins.repo
rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
#yum upgrade -y
yum install epel-release java-11-openjdk-devel
yum install jenkins -y
systemctl daemon-reload
```
