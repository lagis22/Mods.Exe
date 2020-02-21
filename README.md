# Growtopia Mods.exe


## How to use Mods.exe
* Does not need separate http server
* Use HxD or similar to edit "growtopia1.com" and "growtopia2.com" to "localhost" In growtopia binary.
* Alternative: Use hosts file to set growtopia1 and growtopia2 to point to 127.0.0.1 if you want to
* Start Mods -> Run localhost patched file (or normal with hosts) -> Works as supposed

## Features
* Print all variantlists and function calls
* Print all text packets
* Supports modifying, ignoring, and making new packets
* Kill players with wrench
* /legal command to clear malpractice without owning legal briefs
* More commands which you can find in the changelog
* Has a PoC /name name command to call OnNameChanged function for local client.
* Has a PoC OnSpawn modifier which appends netid to each players' name, and gives you unlim zoom
* Can both intercept outgoing and incoming packets
* Integrated http server
* Ignore tracking packets and crash log requests
* Ignore autoban packets (NOTE: you can still get autobanned if the check is serversided)
* Works with subserver switching

## Changelog
# 1.4.2
* Add /mod - shows Mods commands
* Add /tp player - teleports to a player in the world
* Add /ghost - toggles ghost state (you wont move for others when its enabled)
* Major refactor of the whole code
* Add world/player classes, and some helpers for easier adding of new features
* Add solve captcha
* Remove /resolve because its patched


![x](https://i.imgur.com/RG2o9pM.png "Mods pic 3")
![x](https://i.imgur.com/3DFiMgS.png "Mods pic 2")
![x](https://i.imgur.com/Lndhj70.png "Mods pic 1")

