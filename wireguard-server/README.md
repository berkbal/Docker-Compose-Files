Its a ready to go wireguard server container for personal usage. It automaticly generates peers and their configration files for fast usage. There is only 2 variables you should edit before up the container.

**Installation Steps**  

`git clone https://github.com/berkbal/Docker-Compose-Files.git`  
`cd Docker-Compose-Files/wireguard-server`  
Edit line 18 and 14. Put your public ip adress to line 18, and a number for how many clients do you want in your server to 14.  
`docker-compose up -d`  
  
Note: If you have firewall or any software that manages your network, you may have to enable WireGuard's default port. Its 51820. It can be configured via docker-compose.yml.
