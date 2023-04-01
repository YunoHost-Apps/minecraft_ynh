For server administration, use the Minecraft console or mcrcon (which is open on port __PORT__ and uses the password __PASSWORD__).

To use mcrcon, go to `/var/www/minecraft/mcrcon` and type:
```
./mcrcon -p __PASSWORD__ command
```
where `command` is a standard Minecraft command. You must use quotes if your command contains spaces.

You can find more info about the usage of mcrcon here: https://github.com/Tiiffi/mcrcon

The **gamemode** and the **world seed** can be set in the config panel, in the webadmin.
Other settings can be set by modifying `/var/www/minecraft/server.properties`.