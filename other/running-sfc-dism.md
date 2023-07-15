# Running sfc/dism

1. Run command prompt as administrator.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Press <code>Win+R</code>, then type <code>cmd.exe</code> and <strong>press Ctrl+Shift+Enter</strong>.</p></figcaption></figure>

2. Run `sfc /scannow`.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Type <code>sfc /scannow</code> and press Enter.</p></figcaption></figure>

3. After sfc will finish, run `dism /online /cleanup-image /restorehealth`.
4. After dism will finish, reboot your PC.

