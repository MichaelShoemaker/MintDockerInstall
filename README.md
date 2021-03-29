# MintDockerInstall
Purpose: Bash Script to Install Docker and Docker Compose on Linux Mint

## Overview:
This script will uninstall any previous version of Docker and install the latest version as well as install Docker Compose. If you do not want to install Docker Compose simply comment those lines out. They should be clearly indicated at the bottom of the script.

## Note: 
This script has only been tested on Linux Mint 20.1 ulyssa.

The last user to log in is added to the Docker group. You are most likely the last user to log into your system, but if you are on a multiuser system please be aware of this. 

Instructions:
Simply download the MintDockerInstall script and execute the following:

```chmod +x MintDockerInstall```

```sudo ./MintDockerInstall```
