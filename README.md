# Dockeraise
Raise a full Docker setup in your server in seconds!

Simple bash script to automate the installation of Docker on Debian-based servers. 
It also lets you choose if you want to install `docker-compose`, and create a Docker user.

> Only tested on fresh Debian 11 installations. Reviewing the code is recommended.

***
You can either [download](https://raw.githubusercontent.com/Zerodya/dockeraise/main/dockeraise.sh) the script and run it manually, or use the following command:
```
wget -qO- https://raw.githubusercontent.com/Zerodya/dockeraise/main/dockeraise.sh | bash
```
***
### TO DO:
- Check if machine is Debian based (apt)
- Check if Dockeruser UID already exists
