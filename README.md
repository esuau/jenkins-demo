# Jenkins Demo

A repository used to demonstrate the main features of Jenkins CI using the project [javaee7-docker-maven](https://github.com/javaee-samples/javaee7-docker-maven). 

## Install Jenkins on Ubuntu/Debian

Add the repository key to your system: 
```bash
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
```

Then add the following entry in your `/etc/apt/sources.list`: 
```bash
deb https://pkg.jenkins.io/debian-stable binary/
```

Update your local package index, then finally install Jenkins: 
```bash
sudo apt-get update
sudo apt-get install jenkins
```
