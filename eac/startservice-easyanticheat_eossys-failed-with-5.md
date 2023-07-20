# 🔘 StartService EasyAntiCheat\_EOSSys failed with 5

<figure><img src="../.gitbook/assets/eossysfailedwith5.png" alt="" width="398"><figcaption></figcaption></figure>

1. Run the [EAC Fix batch](https://github.com/livingflore/BattleBitEACFix) (download button).
2. Grant EAC full access for application packages in registry.

<figure><img src="../.gitbook/assets/runregedit.png" alt=""><figcaption><p>Press <code>Win+R</code>, type <code>regedit.exe</code> and press Enter.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/uacregistry.png" alt=""><figcaption><p>Press Yes.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/registrypath.png" alt=""><figcaption><p>Go to <code>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/permissions.png" alt=""><figcaption><p>Right click on <code>EasyAntiCheat_EOS</code>.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/grantallapp.png" alt=""><figcaption><p>Click on "Full Control" Allow checkbox under "ALL APPLICATION PACKAGES" group.</p></figcaption></figure>
