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

## Joining Servers
   > Test server is only accessible via [VPN](./vpn).

1. On the multiplayer screen, enter these details for the IP address:
   - Public Server: _TBA_
   - Test Server: [https://drive.google.com/file/d/1E2u4MYnIS4fXtE8vOzikyqyCl7rUsK9U](https://drive.google.com/file/d/1E2u4MYnIS4fXtE8vOzikyqyCl7rUsK9U){:target="_blank"}

   **PLEASE DO NOT SHARE THE SERVER INFO TO ANYONE**
2. Since the server is in `offline-mode`, user whitelisting and authentication is handled differently. When you join a
   server for the first time, the `username` and `password` from your `dungeoncraft-client.yml` config file will be sent
   to the server to trigger the registration, and this message should appear:
 
   `Thank you for registering! Please wait to be whitelisted.`

   These error messages might also appear:

   | Message                        | Resolution                                                   |
   |--------------------------------|--------------------------------------------------------------|
   | User is not whitelisted!       | Please reach out to server admin for whitelisting            |
   | Unable to authenticate player! | Check if you have set up `dungeoncraft-client.yml` correctly |
   | Password is incorrect!         | Check if you have set up `dungeoncraft-client.yml` correctly |
   | User is not registered!        | Server admin disabled registration of new players            |
   | Authentication error!          | Server side error, please reach out to admin                 |
   | Config file missing!           | Check if you have set up `dungeoncraft-client.yml` correctly |

   > Make sure your modpack always matches the server's version before joining. There should be a green
   > checkmark beside the server entry on the selection screen.

