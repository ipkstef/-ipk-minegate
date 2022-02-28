# -ipk-minegate

-ipk-minegate is a customized version of the popular [itzag/mincraft](https://hub.docker.com/r/itzg/minecraft-server) docker image.
Main mod is [Stargate-Network](https://www.curseforge.com/minecraft/mc-mods/stargate-network), found on CurseForge.

**Mincraft Version**: `1.12.2`

**Play with us!**:  Server Address: `mc.stefanos.io`

## Installation

* *Repo is my personal backup, remove everything in [data](./data) except contents in [mods](./data/mods/) folder before first run*

Start the server with DockerCompose

```bash
docker-compose up -d 
```

* Make necessary modifications to [server.properties](./data/server.properties)


## Usage

* Coresponding mod files and Forge version for your client are located in the [client](/client) folder

* Server needs to be restarted after config changes are made

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.



## Mods

* [Stargate-Network](https://www.curseforge.com/minecraft/mc-mods/stargate-network)
    * [Guide(Youtube)]([Stargate-Network](https://www.curseforge.com/minecraft/mc-mods/stargate-network)

* [Davincis-Vessels](https://www.curseforge.com/minecraft/mc-mods/davincis-vessels)
    * [Guide(Youtube)](https://www.youtube.com/watch?v=XaShDt9TYLk)

* [MalisisCore](https://www.curseforge.com/minecraft/mc-mods/malisiscore)

* [MovingWorld](https://www.curseforge.com/minecraft/mc-mods/movingworld)
