# MegaBuiBeo
### Create Windyhell, Tomnotbacon #

Is a simple minecraft host on github

 - Server made by #Tomnotbacon, Windyhell 
 - Config and Host by #WindyHell

### Code: #
 - Server Creating:
    + sudo apt update
    + sudo apt upgrade
 - Java:
    + sudo apt install openjdk-17-jdk (MC 1.17.1)
 - Run:
    + java -Xmx12288M -Xms12288M -jar filename.jar nogui

### Port Forwarding: #
 - Install:
    + wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-arm64.tgz
    + tar -xvzf ngrok-v3-stable-linux-amd64.tgz
 - Host:
    + ./ngrok authtoken “yourtoken”
    + ./ngrok tcp 25565

### Console: #
 - Install:
    + sudo apt install glances
 - Use:
    + glances
