## Installing Docker on Ubuntu
Following are the steps to install docker on Ubuntu 
### Method 1

**lsb_release -a**
This command tells about the running or current version of ubuntu

**sudo apt-get update**

Refreshes the package lists by downloading the latest information from the configured repositories. It does not actually update or upgrade installed packages; it only updates the local database of available software. 

**sudo apt install docker.io**

Install docker package

**sudo systemctl enable docker**

Enable the docker service

**sudo systemctl status docker**

checks wheather docker service running or not

**sudo systemctl start docker**

Starts the docker service if it is not running

**sudo docker run hello-world**

To check docker service we run the above command.
This command pulls the hello-world image from docker-hub , creates a container on local docker system and displays the message "Hello-world".

### Method 2
**lsb_release -a**            
This command tells about the running or current version of ubuntu

**sudo apt-get update**

Refreshes the package lists by downloading the latest information from the configured repositories. It does not actually update or upgrade installed packages; it only updates the local database of available software. 

**curl -fsSL https://get.docker.com -o get-docker.sh**

downloads the **get-docker.sh** script from https://get.docker.com/

 **sudo sh get-docker.sh**
 
Runs the get-docker.sh script  to install the latest stable release of Docker.

**sudo systemctl enable docker**

Enable the docker service

**sudo systemctl status docker**

checks wheather docker service running or not

**sudo systemctl start docker**

Starts the docker service if it is not running

**sudo docker run hello-world**
To check docker service we run the above command.
This command pulls the hello-world image from docker-hub , creates a container on local docker system and displays the message "Hello-world".

**sudo docker run hello-world**

To check docker service we run the above command.
This command pulls the hello-world image from docker-hub , creates a container on local docker system and displays the message "Hello-world".
