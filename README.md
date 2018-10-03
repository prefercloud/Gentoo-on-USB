# Gentoo-on-USB

About

        Boot and run a full-featured Gentoo desktop operating system on USB drive

Requirements

        Any X86-64 based PC/Laptop/Pad with UEFI
        
        For install : A Unix/Linux system with dd & xz and a USB drive with a capacity of 32G or more

Download

        By bittorrent:
        magnet:?xt=urn:btih:33c5510603a5ff3851e9074ce3e0a8391e5bcae4&dn=Gentoo_usb_32G_uefi&tr=http%3a%2f%2f62.210.202.61%3a80%2fannounce&tr=http%3a%2f%2ftracker.vanitycore.co%3a6969%2fannounce&tr=http%3a%2f%2fopen.acgtracker.com%3a1096%2fannounce&tr=http%3a%2f%2ftracker2.itzmz.com%3a6961%2fannounce&tr=http%3a%2f%2feexplodie.org%3a6969/announce

Verifying and validating

        Md5 checksum : 81b850b7838dfbd309ed905a4f60c80d
        Sha512 checksum : b459bb1c3daf2550dbcf7609a6468d05bcc2823492ba79feacc68e1844332fe78832f7e1a7313424bf14a6029f0a54568f5cb0f96b6a2c272639b8304c0e0b21

Install
        
        xz -dck /path/to/Gentoo_usb_32G_uefi.xz | dd of=/dev/sdX bs=64K status=progress
        (Change /dev/sdX to actual USB drive path)

        The default root/user password is : Secret555
        Please change your password as soon as possible

Update and install software (on terminal)
     
       emerge --sync
       eix-update

       eix "software name"
       emerge "software name"

       You can get help from Gentoo handbook and Gentoo forums(https://forums.gentoo.org/)

Tested Hardware

       PC/Laptop/Pad:

       Apple Macbook pro 14.3/2017 (Audio/Wifi not working. please check : https://github.com/Dunedan/mbp-2016-linux )
       Apple Macbook pro 2011
       MICROSOFT SURFACE PRO 3
       HP Elitebook 2560p/8560p
       Dell Precision M6700
       Lenovo ThinkCentre M72e Tiny

       Motherboard:

       ASUS P8Z68-V PRO/GEN3

Support Hardware
   
       Wifi: Atheros/Intel/Ralink/MediaTek/Realtek
     
Recommended USB Drive

       All SanDisk USB 2.0 and USB 3.0 Flash Drive
