# Alienware-Aurora-R11-OSX-Install-Opencore

Glad to have success on the install, I purchased this Alienware Aurora R11 with Intel i7 10700 with RTX 2070 Super.

Obviously I have to swap out the GPU, I purchased and replaced it with the MSI RX5700XT.

Updated Second Version
The config is based on: https://github.com/michaelsunzy/Hackintosh-Alienware-R11-OpenCore-i9-10900KF-Z490
- Made Updates to Supper Multiple Monitors with mt video card (6900xt)
- Try to change your BIOS settings to this: https://www.reddit.com/r/hackintosh/comments/qwxddn/alienware_aurora_r11_hackintosh/
- Stable enough for daily use now, it is on BigSur.

First Version:
The config file is based on: https://hackintosher.com/forums/thread/success-guide-opencore-gigabyte-z490-gaming-x-i7-10700-monterey-big-sur-catalina.10745/
Running on Opencore 0.73

What is working?

- BigSur 10.6
- Sound
- Ethernet
- USB Mapped

What is not working?
- Does not seem to sleep.
- BT (I used an ASUS dongle which works fine)
- WIFI (will need to replace the wifi module I believe)

Overall I am very happy with the performance, I have used RadeonBoost.kext and I believe improves the graphics.

Remember to generate your own SN, MLB, UUID with https://github.com/corpnewt/GenSMBIOS


