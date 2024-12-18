# How to run

### On Windows
Open Docker Desktop, then run the docker container to make your Minecraft Server.
```
docker compose up -d
```
### On Linux
Enter the repository
```
cd Minecraft-Docker
```
Run the docker container
```
sudo docker compose up -d
```

## Bluemap
To enable the Bluemap Mod, you will need to go into the data folder and find the config files of Bluemap, you then need to switch it from false to true and restart the container.
If you do not want to play with Bluemap, you can simply remove it from the file `docker-compose.yml` before you run the file the first time. If you've already run the docker container, you will need to manually remove it from the mods folder as well.

# Port Forwarding
Go into your ISP's router control and forward the ports 25565 (Minecraft) and 8100 (bluemap).
