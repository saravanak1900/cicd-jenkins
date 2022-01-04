# cicd-jenkins
## Jenkins tutorial
### Install STABLE LTS Jenkins 
####################################

```
sudo -i
wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat/jenkins.repo

rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key
yum install jenkins -y

systemctl restart jenkins;systemctl enable jenkins;systemctl status jenkins
```
