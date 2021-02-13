# Minecraft Server for YunoHost
 
[![Install Minecraft with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minecraft)

> *This package allows you to install Minecraft Server quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Minecraft is a sandbox construction game, whose gameplay involves players interacting with the game world by placing and breaking various types of blocks in a three-dimensional environment. In this environment, players can build creative structures, creations, and artwork on multiplayer servers and singleplayer worlds across multiple game modes. 

**Shipped version:** 1.16.5 (Vanilla version)

## Configuration

### Installing guide

The app can be installed by **running the following command**:

`sudo yunohost app install https://github.com/YunoHost-Apps/minecraft_ynh`
         
For server administration, use the Minecraft console or RCON (which is open on port 25575 with your password).

### Rcon Clients

- https://github.com/Tiiffi/mcrcon/releases (in C)

### Start/Stop/Restart/Check Status Minecraft

- ```systemctl start minecraft```
- ```systemctl stop minecraft```
- ```systemctl restart minecraft```
- ```systemctl status minecraft```

### Location

The folder of your servers is: `/home/yunohost.app/`

### Supported Servers
 
1. Minecraft (Vanilla)
2. Minecraft (Vanilla snapshot)
3. Spigot
4. CraftBukkit (by Spigot)
5. BungeeCord
6. Paper
7. Waterfall (by Paper)
 
### Upgrade this package

```
sudo yunohost app upgrade minecraft -u https://github.com/YunoHost-Apps/minecraft_ynh
```

## Documentation

 * Non-official documentation: https://minecraft.gamepedia.com/Tutorials/Setting_up_a_server

## YunoHost specific features

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/minecraft_ynh/issues
 * App website: https://www.minecraft.net/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/minecraft_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minecraft_ynh/tree/testing --debug
or
sudo yunohost app upgrade minecraft -u https://github.com/YunoHost-Apps/minecraft_ynh/tree/testing --debug
```
