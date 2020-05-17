# Lenovo-G50-80-Mojave-Opencore
I compiled this EFI folder to install macOS Mojave on a Lenovo G50-80. 
Using Opencore 0.5.8 it's working with minor issues, most of them unimportant.  

Specs for my machine: 
Model: Lenovo G50-80
Bios version: B0CNA0WW
CPU: i7 5500U, HD 5500 Graphics
RAM: 4GB
Hard drive: 128GB SATA SSD
Audio: Conexant CX20752
Ethernet: RTL8111 

Known Issues:  
*Trackpad doesn't appear under System Preferences->Trackpad. Meaning only mouse movement and two finger scrolling works (Vertical and Horizontal).  
*WiFi obviously doesn't work with the default WAN card, it being Intel. You either have to use a usb dongle or replace it with a working one. See the Wireless Buyer's Guide on dortania.  


If your setup is almost identical to mine you can use this EFI folder and try your luck. I removed serial numbers so you'll have to generate new ones to use with GenSMBIOS.
