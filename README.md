# DOCKER-CE (Community Edition) 

###### Docker Remove

* ``` sudo yum remove docker docker-client docker-client-latest docker-common docker-latest docker-latest-logrotate docker-logrotate docker-selinux  docker-engine-selinux docker-engine ```

###### Docker Install

* ``` sudo yum install -y yum-utils device-mapper-persistent-data lvm2 ```
* ``` sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo ``` 
* ``` sudo yum install docker-ce```

* ``` sudo systemctl enable --now docker ```

* ``` sudo systemctl status docker ```

###### Docker Compose Install

* ``` sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose ```

* ``` chmod +x /usr/local/bin/docker-compose ```

* ``` docker-compose -v ``` or --version

* ``` https://docs.docker.com/compose/install/ ``` - check docker-compose latest version 
