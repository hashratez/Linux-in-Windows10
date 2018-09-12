# Linux-in-Windows10
How to run Ubuntu in Windows so you can run a EveryCash Node, Wallet &amp; Miner

Requred: Windows Fall 2017 Creators Update, which is Windows build 16215, aka Redstone 3. The most complex step is doing the following: In search, type “powershell,” right-click this, and select “Run as administrator”.  Or right click Windows Button (lower left) and select "Windows PowerShell Admin"  Or  Enter the following command:
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
WINDOW WILL ASK YOU TO INSTALL WHEN YOU HIT "Y" FOR YES IT WILL INSTALL IN THE SHELL AND THEN REBOOT WITHOUT ASKING!  BE READY!!!!

Go to the Windows STore and search "Linux" select "Ubuntu 18.04" and install.  This takes a few minutes.

During install you will get a shell window.  Wait, it will ask for username & pass.  Walla, you've got Ubuntu.  Follow the instructions on EveryCash to install the coin.

Enjoy!
