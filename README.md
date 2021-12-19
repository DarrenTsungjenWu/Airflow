# Airflow
### Prerequisite: Docker, Docker Compose, Airflow python package index

### Quick Note:

### Docker 
##### Install
> Go to and download
https://www.docker.com/get-started

When being done, it will be seen that the file Docker Desktop Installer.exe is set.
Install it.

> Register an Docker user account (ID and password) for future log-in use.

##### Docker Running

When Docker is going to be run, a common issue will be shown that WSL2 installation is not complete. This happens due to old version of WSL2 to be executed.

For this case, click into the link shown in the pop-out warning window, and follow it: https://docs.microsoft.com/zh-tw/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package

Starting from step 4 in that, one downloads the most current version of WSL2 (For Windows System, Ubuntu is often used to run Docker on Linux. See step 5).

Otaining Ubuntu and setting up your Ubuntu user account (step 5 and 6), you sucessfully access Linux version that is integrated with Windows System using Ubuntu.

Restart PC and Docker can be run through this way.


##### Docker Test Installation
To simpy test Docker, try in cmd that
> docker -v

to get short information about Docker version

can also trying:

> docker run hello-world

so the containers from this "image" will be established so that the process can be executed.


### Docker Compose
##### Install
> Visit official documentation: https://docs.docker.com/compose/install/

Go down and select Linux tab if Linux is used.

Run the command on Ubuntu
> curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

or

> sudo curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

in terminal to get latest/specific release of Docker Compose.

And apply executable permission
> sudo chmod +x /usr/local/bin/docker-compose

If all is already applied, try in Ubuntu that
> docker-compose --version

to test the docker-compose installation.


### Python Package Index
> pip install apache-airflow

via python terminal

official doc. 
> https://pypi.org/project/apache-airflow/


### Airflow
##### Quick start Airflow - an example airflow package below
To clone the repo by "Git Bash" 
> git clone https://github.com/DarrenTsungjenWu/airflow-tutorial.git

(HTTPS)

after this one changes directory of bash to airflow-tutorial
> cd airflow-tutorial

run
> docker-compose up

For detailed information about above steps, can see following tutorials 
> Github: https://github.com/DarrenTsungjenWu/airflow-tutorial

and subsequent Youtube tutorial
> https://www.youtube.com/watch?v=vvr_WNzEXBE&ab_channel=TuanVu

Finally, check how airflow works by visiting
> http://localhost:8080
