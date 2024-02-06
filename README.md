# XitecOS
Linux distribution

"I have created a Linux distribution based on Debian Testing and MX Linux, and, what can I say, it is fast, very fast, and very user-friendly. It is a live system with an installer, and I hope that others will test it.

XitecOS is based on Debian Testing and prefers the packages of this repository but I've added the following repositories:

    -Debian Trixie
    -Debian Bookworm
    -Debian Sid
    -MX Linux
    -Miscrosoft(Visual Studio Code)
    -Penguin's Eggs (for backups with eggs)
    
Overview:

    -If you install any programm it will be installed from Debian Testing(Trixie) except the grub bootloader(bookworm).
    -Kernel Updates are from the MX Linux ahs(Advanced Hardware Support) repository(it's a Liquorix Kernel).
    -The XFCE4 Desktop is patched with the MX Linux version
    -If you want to install from Sid you can type 'sudo apt install PRGRAMNAME/sid' for example.

Advantages of Debian Testing:

    Rolling Release: Debian Testing is a rolling release distribution, providing users with access to the latest software updates and features without the need for a complete system upgrade.
    Up-to-date Software: Users can benefit from relatively recent versions of software packages, striking a balance between stability and cutting-edge features.
    Community Support: Debian has a large and active community, ensuring excellent support and a wealth of resources for users.

So if you want to be up to date, you press [F4] to open console and type:
--------------------------------------------------
     sudo apt update -y
     sudo apt upgrade -y
     sudo apt full-upgrade -y
     sudo apt dist-upgrade -y
--------------------------------------------------

Advantages of MX Linux:

    Lightweight and Efficient: MX Linux is known for its efficiency and low system resource requirements, making it suitable for older hardware(in this case amd64 only) or systems with limited resources.
    Customization: MX Linux provides a user-friendly interface with a range of customization options, allowing users to tailor the desktop environment to their preferences.
    MX Tools: MX Linux includes a set of tools (MX Tools) that simplify various tasks, enhancing the overall user experience.

# XFCE Edition - full Desktop Environment with all tools installed

    -uses the grub bootloader from Debian stable(bookworm) to facing issues with the current and future version(s)
    -uses the MX Linux Style XFCE4 Desktop
    -you have everything preinstalled:
        -audio-/videoplayer, internet radio
        -'winff' audio-/videoconverter
        -'recordmydesktop' screencast tool
        -libreoffice
        -geanny, idle and visual studio code IDE
        -XitecOS backup(build your own live system of your system with calamares installer)
        -ventoy 1.0.97 for creating Multiboot USB drives(install it to USB and just copy .iso and .img images to it, and boot it)
        -GIMP photo editor
        -openshot video editor
        -the most of the MX-tools
        -the everywhere condele by pressing 'F4' like in MX Linux (I LOVE THIS CONSOLE)
        
#-------------

# CLI Edition(v0.9):

If you run the live system:

-It asks automaticly for installing XitecOS CLI edition

IMPORTANT: CLI EDITION CAN'T BE INSTALLED ALONGSIDE AN OTHER OPERATING SYSTEM

If you run the installed system:

-It asks automaticly for setting up WIFI connection

-It asks if you wish to install a Desktop-environment
    with or without programs preinstalled
      if you want to setup everything on your own

# THE FOLLOWING DESKTOPS ARE SUPPORTED:

    -xfce4
    -gnome
    -mate
    -cinnamon
    -lxqt
    -lxde
    -unity
    -budgie
    -kde-plasma
    -pantheon


If you want to setup a Debian Testing from the bottom with a liquorix kernel and the desktop of your choice this is your chance

# Download for amd64 only at my google drive
https://drive.google.com/drive/folders/1qUTAkEv4vk_45YkdHC3HCwyVi5ToJaLM?usp=sharing
----------------------------------------------------
     login:    xitec
     password: xitec
----------------------------------------------------
