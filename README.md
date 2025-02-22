![logo](https://mclo.gs/img/logo.png)

With this plugin, you can upload your Minecraft server log to [mclogs](https://mclo.gs) directly from your server
with one simple command. It's even possible to export old server log files, e.g. after a crash. Critical information 
like IP addresses are automatically hidden to ensure safety and privacy.

### Downloads
- [GitHub Releases](https://github.com/aternosorg/mclogs-bukkit/releases)
- [Spigotmc](https://www.spigotmc.org/resources/mclo-gs.47502/)
- [CurseForge/DevBukkit](https://www.curseforge.com/minecraft/bukkit-plugins/mclogs)
- [Modrinth](https://modrinth.com/plugin/mclogs)

### Commands
```
/mclogs
```
Upload the current server log

```
/mclogs list
```
List all currently available server logs and upload them with one click.
```
/mclogs share <filename>
```
Share a specific log file, .gz files are automatically unpacked.

### Developing
This plugin uses the [mclogs-java](https://github.com/aternosorg/mclogs-java) library.
You need to run the following command to add it to the project:
```bash
git submodule init && git submodule update
```