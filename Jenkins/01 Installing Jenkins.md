# Installing Jenkins:
```
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | gpg --import -
sudo sh -c 'echo "deb https://pkg.jenkins.io/debian-stable binary/" > /etc/apt/sources.list.d/jenkins.list'
sudo apt-get update
sudo apt-get install jenkins

sudo systemctl start jenkins
sudo systemctl status jenkins
```
