# Linux-in-Windows10
How to run Ubuntu in Windows so you can run a EveryCash Node, Wallet &amp; Miner

Fall 2017 Creators Update, which is Windows build 16215, aka Redstone 3. The most complex step is doing the following: In search, type “powershell,” right-click this, and select “Run as administrator” (see image below). Enter the following command, and restart your system:
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
