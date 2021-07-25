# MintDockerInstall
Purpose: Bash Script to Install Docker and Docker Compose on Linux Mint

## Overview:
This script will uninstall any previous version of Docker and install the latest version as well as install Docker Compose if the script is executed using the keyword "all".

## Note: 
This script has only been tested on Linux Mint 20.1 Ulyssa and Linux Mint 20.2 Uma.
The last user to log in is added to the Docker group. You are most likely the last user to log into your system, but if you are on a multiuser system please be aware of this. 

Instructions:
Simply download the MintDockerInstall script and execute the following:

```sudo chmod +x MintDockerInstall```

```sudo ./MintDockerInstall```
or to install compose as well
```sudo ./MintDockerInstall all```

You will be prompted for the current users password once the script has completed. 
