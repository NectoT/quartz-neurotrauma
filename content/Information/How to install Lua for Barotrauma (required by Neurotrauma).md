# How to install Lua for Barotrauma (required by Neurotrauma)

Original URL: https://trello.com/c/8peFj5ez

---

[Lua for Barotrauma](https://steamcommunity.com/sharedfiles/filedetails/?id=2559634234 "‌") is a Barotrauma modification that adds Lua and Cs modding, this is not a direct replacement for XML, but works great in doing things that weren't possible in XML.

### How to Install Lua: Check out the [Lua for Barotrauma](https://steamcommunity.com/sharedfiles/filedetails/?id=2559634234 "‌") workshop page for specific installation guide for your OS.

# Server Side Lua:

Many Lua mods are server-sided, meaning Lua is only required to work on the server for those mods to work, to enable the mod on the server-side simply select the Server Executable when in the hosting menu.
**If you want to checkout if the Lua is working properly on the server, open the debug console (F3) and run the command "reloadlua"**

Note: This obviously doesn't work if you play on singleplayer, for that you will need to install Client-side Lua.

# Client Side Lua:

Client-side Lua is when the mod is running in your game client, many mods make use of it to either do more extensive changes to the game or to add singleplayer support.

For example [Neurotrauma](https://steamcommunity.com/sharedfiles/filedetails/?id=3190189044 "‌") will work mostly fine if you are playing multiplayer and only the server has Lua installed, it straightforward won't work on singleplayer if you don't have Client-side Lua installed, while -as examples- [NT Eyes](https://steamcommunity.com/sharedfiles/filedetails/?id=3294574390 "‌") and [NT Cybernetics Enhanced](https://steamcommunity.com/sharedfiles/filedetails/?id=3324062208 "‌") (Neurotrauma expansions) require both Server-side Lua and Client-side Lua to work properly on **multiplayer**, that means for these mods, everyone will need Client-side Lua installed for it to work properly. It depends on each mod, so consult the description/author of the mod to make sure.

**If you want to checkout if the mod is working properly on the client, open the debug console (F3) and run the command "cl_reloadlua".**

For any further questions regarding Lua you can join the [Luatrauma discord server](https://discord.gg/f9zvNNuxu9 "‌").

---

## Attachments

id | original fileName | image
---|---|---
[6718845db30472d958dd7e7d](./How%20to%20install%20Lua%20for%20Barotrauma%20(required%20by%20Neurotrauma)%20-%20Attachments/6718845db30472d958dd7e7d.png) | 1200px-Lua-Logo.svg.png | ![1200px-Lua-Logo.svg.png\|200](./How%20to%20install%20Lua%20for%20Barotrauma%20(required%20by%20Neurotrauma)%20-%20Attachments/6718845db30472d958dd7e7d.png)