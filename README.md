# Airflow
### Prerequisite: Docker, Docker Compose, Airflow python package index

### Quick Note:

#### Docker 
##### Install
> Go to and download
https://www.docker.com/get-started

When being done, it will be seen that the file Docker Desktop Installer.exe is set.
Install it.

> Register an Docker user account (ID and password) for future log-in use.

##### Docker Running

When Docker is going to be run, a common issue will be shown that WSL2 installation is not complete. This happens due to old version of WSL2 to be executed.

For this case, click into the link shown in the pop-out warning window: https://docs.microsoft.com/zh-tw/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package

Starting from step 4, we download the new version of WSL2 and then follow the guide in it. (For Windows System, Ubuntu is often used to run Docker on Linux. See step 5).

Otaining Ubuntu and setting up your Ubuntu user account (step 5 and 6), you sucessfully access Linux version that is integrated with Windows System.

Restart PC and Docker can be run through this way.


#### Docker Compose
##### Install
> Visit: https://docs.docker.com/compose/install/
Go down and select Linux tab is Linux is used.

Run the command
> curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
or
sudo curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

in terminal to get latest/specific release of Docker Compose.

After this, follow the guide down this to complete the installation. 


#### Python Package Index



#### Airflow
##### Quick start Airflow
Can do this by following tutorials 
Github > https://github.com/DarrenTsungjenWu/airflow-tutorial
and subsequent Youtube tutorial
> https://www.youtube.com/watch?v=vvr_WNzEXBE&ab_channel=TuanVu

