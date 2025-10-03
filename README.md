This firmware is for the halot mage PRO. It is modded to include more features such as:
Root access, SSH, SCT file trasnfer, Drag and drop - Windows file explorer network transfers.

This firmware version is only for English as space had to be saved via font modification.




How to use

1.Place Chituupgrade.bin in direct folder on USB on its own.

2.Turn on printer and assure you see a green line across the bottom of the screen.

3.Once the screen goes blank and turns back on remove USB.

--------------------------------------------------------------------------------------

Use these steps to make network in windows 11 work for drag and drop file sharing.

1.Using Group Policy

Press Win + R, type gpedit.msc and hit Enter.

Navigate to:


Enable insecure guest and disable SMB signing (easiest on a private network)

Press Win + R, type gpedit.msc, and hit Enter.

Navigate to:Computer Configuration → Administrative Templates → Network → Lanman Workstation


2.(still in Group Policy) 

Enable “Enable insecure guest logons”.

disable SMB signing requirement: Computer Configuration → Windows Settings → Security Settings → Local Policies → Security Options

Find Microsoft network client: Digitally sign communications (always) → set to Disabled

Find Microsoft network client: Digitally sign communications (if server agrees) → set to Enabled


3.Reboot Windows.


--------------------------------------------------------------------------------------
Don't bother with GUI upgrade from USB screen. Just power off and insert USB with chituupgrade.bin on main directory of USB(fat32).
Use the use it comes with or any other that flashes to let you know it's working. It shouldn't take over a minute though.

Change backgrounds and other icons and all here: /customer/resources/images

Login:root Password:passwd
