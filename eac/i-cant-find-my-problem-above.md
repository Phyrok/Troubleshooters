---
cover: ../.gitbook/assets/achelp.png
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🤨 I can't find my problem above

If you can't find your issue in the page list or those instructions don't help you, reach out to [#anti-cheat-help](https://discord.com/channels/303681520202285057/1023557300214050968) in the [BattleBit Discord server](https://discord.com/battlebit) for assistance.\
\
When asking for help, please attach the following information:

1. Screenshot of the error
2. `service.log`:
   - Windows: `%appdata%\EasyAntiCheat`
   - Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/EasyAntiCheat`
3. `loader.log`:
   - Windows: `%appdata%\EasyAntiCheat\43ed9a4620fa486994c0b368cce73b5d\315826d981f4480aa6155e32d71b0d3b`
   - Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/EasyAntiCheat/43ed9a4620fa486994c0b368cce73b5d/315826d981f4480aa6155e32d71b0d3b`
4. `player.log`:
   - Windows: `C:\Users\%username%\AppData\LocalLow\BattleBitDevTeam\BattleBit\`
   - Linux (Proton): `~/.local/share/Steam/steamapps/compatdata/671860/pfx/drive_c/users/steamuser/AppData/LocalLow/BattleBitDevTeam/BattleBit`

To navigate to the required folders:
- On Windows, press Win+R and paste the needed path to access the folder.
- On Linux, use the terminal or a file explorer GUI to navigate to the specified path.

{% hint style="info" %}
The Linux paths are only there if you use Proton with Steam, otherwise you can use a command like `find ~/ -name player.log` etc. to find the file.
{% endhint %}