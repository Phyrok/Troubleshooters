---
description: Beside EAC, your connection can also cause this issue.
cover: ../.gitbook/assets/redtext.png
coverY: 0
---

# 🔘 Make sure you have installed EasyAntiCheat and run the game with it

<details>

<summary>Step 1 - Run the <a href="https://github.com/livingflore/BattleBitEACFix">EAC Fix batch</a></summary>

1. Go to [github repo](https://github.com/livingflore/BattleBitEACFix).
2. Press ![](../.gitbook/assets/downloadbutton.svg) button.
3. Run the batch.
4. You should see output as shown [here](https://i.imgur.com/kHZGKkk.png).

</details>

<details>

<summary>Step 2 - VCRedists</summary>

Ensure that **BOTH** VCRedists installed properly - [x86](https://aka.ms/vs/17/release/vc\_redist.x86.exe) and [x64](https://aka.ms/vs/17/release/vc\_redist.x64.exe). When running installers you should see 3 buttons - repair, uninstall and cancel as on screenshot below. If you can't see it - proceed with installation.

<img src="../.gitbook/assets/vcredistx64.png" alt="" data-size="original"><img src="../.gitbook/assets/vcredistx86.png" alt="" data-size="original">

</details>

<details>

<summary>Step 3 - Running executables as admin</summary>

Try running `BattlebitEAC.exe` or `EasyAntiCheat.exe` as admin located in installed files.

1. Right click on the game, then go to manage and click on Browse local files.

<img src="../.gitbook/assets/browse.png" alt="Right click on the game, then go to manage and click on Browse local files" data-size="original">

2. Right click on executable and click "Run as administrator".

<img src="../.gitbook/assets/runasadmin.png" alt="Right click on executable and click &#x22;Run as administrator&#x22;." data-size="original">

</details>

<details>

<summary>Step 4 - Connectivity issues</summary>

This issue can happen when your connection unstable / Steam is down / you can't reach either EAC or BattleBit servers.

1. Check Steam if you're in offline mode.
2. Disable malware protection and firewall if you use third party antivirus (Kaspersky, Avast, etc)
3. Try to use mobile hotspot instead of your main internet connection just to launch the game. If it happens that you don't have it, proceed to the next step.
4. Use any **private** VPN or [Cloudflare WARP](https://install.appcenter.ms/orgs/cloudflare/apps/1.1.1.1-windows-1/distribution\_groups/release).

</details>
