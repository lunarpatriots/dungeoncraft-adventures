---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
permalink: /phtb/
---

# SETUP GUIDE

## Prerequisites
- [Modrinth](./modrinth)
- [CurseForge](./curseforge)

## Core Config

1. Launch the modpack, then click on the `Mods` button to open the modlist.
2. Search for the mod `DungeonCraft Core`, then double click to open the config editing screen.
3. You should see textboxes for `username` and `password`. These will be used to register/verify your account whenever
   you join a server that also uses this modpack.

   **DO NOT INPUT A PASSWORD THAT YOU ALSO USE ON PERSONAL ACCOUNTS!**
4. Save your changes. No need to restart.

## Joining Servers

1. On the multiplayer server selection screen, click on `Add Server` and enter this server address:
   - Public Server: _TBA_
   - Test Server: [link](https://drive.google.com/file/d/1E2u4MYnIS4fXtE8vOzikyqyCl7rUsK9U){:target="_blank"}
     (only accessible via [VPN](./vpn))

   **PLEASE DO NOT SHARE THE SERVER ADDRESSES TO THE PUBLIC**
2. Since the server is in `offline-mode`, user whitelisting and authentication is handled differently. When you join the
   server for the first time, the `username` and `password` you entered earlier will be registered to the server, and 
   you should see this message:
 
   `Thank you for registering! Please wait to be whitelisted.`

   These error messages might also appear:

   | Message                        | Resolution                                                                                    |
   |--------------------------------|-----------------------------------------------------------------------------------------------|
   | User is not whitelisted!       | Please reach out to server admin for whitelisting                                             |
   | Unable to authenticate player! | Check if you have set up your `username`/`password` on the DungeonCraft Core config correctly |
   | Password is incorrect!         | Check if you have set up your `username`/`password` on the DungeonCraft Core config correctly |
   | User is not registered!        | Server admin disabled registration for new players                                            |
   | Authentication error!          | Server side error, please reach out to admin                                                  |
   | Config file missing!           | Check if you have set up your `username`/`password` on the DungeonCraft Core config correctly |

   > Make sure your current modpack version always matches the server's version before joining. There should be a green
   > checkmark beside the server entry on the selection screen.