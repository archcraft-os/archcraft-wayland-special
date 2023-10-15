<p align="center">
<a href="https://archcraft.io"><img src="https://raw.githubusercontent.com/archcraft-os/archcraft-packages/main/archcraft-artworks/files/logo/png/logo-circle/logo-circle-1.png" height="128" width="128" alt="Archcraft"></a>
</p>

<p align="center">
<b>Archcraft Wayland Special Edition : An Ultimate Wayland Compositors Experience</b>
</p>

<p align="center">
  <a href="https://archcraft.io" target="_blank"><img alt="home" src="https://img.shields.io/badge/HOME-blue?style=flat-square"></a>
  <a href="https://wiki.archcraft.io" target="_blank"><img alt="wiki" src="https://img.shields.io/badge/WIKI-blue?style=flat-square"></a>
  <a href="https://archcraft.io/gallery" target="_blank"><img alt="screenshots" src="https://img.shields.io/badge/SCREENSHOTS-blue?style=flat-square"></a>
  <a href="https://www.reddit.com/r/archcraft" target="_blank"><img alt="reddit" src="https://img.shields.io/badge/REDDIT-blue?style=flat-square"></a>
  <a href="https://discord.gg/3PzeJ5S7Pu" target="_blank"><img alt="discord" src="https://img.shields.io/badge/DISCORD-blue?style=flat-square"></a>
  <a href="https://t.me/archcraftos" target="_blank"><img alt="telegram" src="https://img.shields.io/badge/TELEGRAM-blue?style=flat-square"></a>
  <a href="https://matrix.to/#/#archcraft:matrix.org" target="_blank"><img alt="matrix" src="https://img.shields.io/badge/MATRIX-blue?style=flat-square"></a>
</p>

[![gif](./wayland.gif)](https://ko-fi.com/s/213becbf00)

---

### From Archcraft Wiki

- [Things To Do After Installing Archcraft](https://wiki.archcraft.io/docs/install-archcraft/post-install)
- [Install Archcraft With Calamares](https://wiki.archcraft.io/docs/install-archcraft/install-with-calamares)
- [Install Archcraft With ABIF](https://wiki.archcraft.io/docs/install-archcraft/install-with-abif)
- [Create A Bootable USB With Archcraft](https://wiki.archcraft.io/docs/boot-iso/boot-with-usb)
- [Boot Archcraft ISO With GRUB2 Bootloader](https://wiki.archcraft.io/docs/boot-iso/boot-with-grub)

### Overview
This special edition of Archcraft comes with [`Sway`](https://github.com/archcraft-os/archcraft-sway), [`Wayfire`](https://github.com/archcraft-os/archcraft-wayfire), [`River`](https://github.com/archcraft-os/archcraft-river), [`Hyprland`](https://github.com/archcraft-os/archcraft-hyprland) and [`Newm`](https://github.com/archcraft-os/archcraft-newm) pre-installed, pre-configured and provides you a wayland only Linux experience.

**1st ISO Generation :** `October 20th, 2022` <br>
**2nd ISO Generation :** `January 10th, 2023` <br>
**3rd ISO Generation :** `April 15th, 2023` <br>
**4th ISO Generation :** `May 6th, 2023` <br>
**5th ISO Generation :** `July 11th, 2023` <br>
**6th ISO Generation :** `October 15th, 2023` <br>
**Last Updated :** `October 15th, 2023`

<details>
<summary><b>Changelogs</b></summary>

### Changelog (October 2023) : 6th ISO
- Updated ISO profile
- Latest base with new packages
- Updated all wayland compositors
  - Added better example for multi-monitor support in...
    - Sway: `~/.config/sway/sway-output`
    - Wayfire: `~/.config/wayfire.ini`
    - River: `~/.config/river/init`
    - Hyprland: `~/.config/hypr/hyprland.conf`
    - Newm: `~/.config/newm/config.py`
- Added `wipe` ability in ABIF
- Fixed issue with `help and tips` app
- Small improvements and bugs fixed.

#

### Changelog (July 2023) : 5th ISO
- Updated ISO profile with latest archiso
- Latest base with new packages
- Fixed sddm not saving the last used session issue
- Added a calculator app
- Added Welcome and Help-and-Tips App
- Fixed Scaling issue in QT apps in wayland
- **`Sway, Wayfire, River, Hyprland`**
  - Added `bluetooth` module on Waybar
  - Added a rofi `bluetooth` applet
  - Added `alacritty` terminal
  - Added `pywal` support
  - Improved a lot of scripts
  - etc
- Many small bugs fixed.

#

### Changelog (May 2023) : 4th ISO
- Fixed pacman-init issue
- Added ability to choose desktop in the installer (calamares)
- Fixed auto-login issue
- etc

#

### Changelog (April 2023) : 3rd ISO
- Using `sddm-git` now, Solved shutdown/reboot issue
- Using new method to boot the ISO on Nvidia Machines
- Updated the Installers with (possible) Nvidia support
- Updated the base system with latest packages
- **`Updated All the wayland compositors`**
  - Updated the config structure
  - Added Rofi menu, applets and scripts (network, music, etc)
  - Fixed area screenshot overlay issue
  - Fixed nerwork-applet overlay issue in hyprland
  - Modified the configs for waybar, wlogout and wofi (added separate colors.css file)
  - Changes gtk themes in sway, wayfire and hyprland
  - Updated lockscreen script in sway
  - Added two packages for NEWM (one normal and one blur)
  - Added spotify module in waybar in all WCs
  - Animated MPD and spotify modules in waybar
- Many Bug fixes, etc

#

### Changelog (January 2023) : 2nd ISO
- Added ABIF (CLI) installer
- Updated the base system
- Updated All the compositors
- Bug fixes, etc

#

### Changelog (October 2022) : 1st ISO
- Created the ISO base from scratch
- Grub2 bootloader with themes
- Customized Plymouth & SDDM
- Basic Applications Only, No Bloatware
- Calamares Installer (Graphical)
- Full Network Manager Support, Various VPN plugins
- Built-in Bluetooth Support
- Pipewire For Sound/Audio (Systemwide, Bluetooth, Jack)
- Built-in Printer Support
- Almost All Audio, Video and Image Codecs
- Full File manager functionality (Mounting, Networking, Archiving, etc)
- Built-in AUR support
- Minimal User Interface
- Multiple Wayland Compositors (Sway, Wayfire, River, Hyprland, Newm)
- Archcraft Icons, Themes, Wallpapers, Fonts
- Etc

</details>

### Get The ISO

You can download the latest `ISO` from [ko-fi :coffee:](https://ko-fi.com/s/213becbf00).

> Default `username` and `password` is **liveuser**.

For Graphical Installation Instructions, See [Install Archcraft With Calamares](https://wiki.archcraft.io/docs/install-archcraft/install-with-calamares)<br>
For CLI (abif) Installation Instructions, See [Install Archcraft With ABIF](https://wiki.archcraft.io/docs/install-archcraft/install-with-abif)

---

**`WARNING : VM -`** This ISO does not work with **VMs (Virtualbox, VMware, Qemu, etc)**. I mean it does but... on some, you won't pass the login screen (SDDM) and on some, the compositors will be very laggy due to poor 3D support.

#
<br>

**`WARNING : Nvidia -`** There is no official support for Nvidia. Unfortunately, their drivers are so messy, and their products so random, that it’s impossible to help if the ISO don’t work on your machine. Every card seems to be random, and might work perfectly, or not work at all. However...<br>
The `lastest ISO (April 15th)` have everything configured **out-of-the-box**, Needed to run a _wayland compositor_ on **Nvidia**. It has all the needed modules enabled into `mkinitcpio.conf` and **initrd**, `Kernel parameters` are added, and the needed proprietary graphics drivers installed.<br>
Now, It's your choise to give it a try.

**Update:** As Reported, Users are able to boot and Install the Latest ISO (April) on their Nvidia Machines. Everything is working fine.

**More info :** [Sway Installation](https://wiki.archlinux.org/title/Sway#Installation), [Hyprland Nvidia](https://wiki.hyprland.org/Nvidia/), [wayland Requirements](https://wiki.archlinux.org/title/wayland#Requirements), [DRM_kernel_mode_setting](https://wiki.archlinux.org/title/NVIDIA#DRM_kernel_mode_setting), [NVIDIA#Installation](https://wiki.archlinux.org/title/NVIDIA#Installation)

#
<br>

**`WARNING : Iris XE -`** Some users reported that, This ISO does not work on systems with `Intel Iris XE` GPUs.

---

### Screenshots

<!-- Sway -->

<details>
<summary><b>Sway</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 |
| --- | --- | --- | --- |
|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_1.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_2.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_3.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_4.png)|

</details>

<!-- Wayfire -->

<details>
<summary><b>Wayfire</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_1.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_2.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_3.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_4.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_5.png)|

</details>

<!-- River -->

<details>
<summary><b>River</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 |
| --- | --- | --- | --- |
|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_1.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_2.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_3.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_4.png)|

</details>

<!-- Hyprland -->

<details>
<summary><b>Hyprland</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 |
| --- | --- | --- | --- |
|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_1.png)|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_2.png)|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_3.png)|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_4.png)|

</details>

<!-- NEWM -->

<details>
<summary><b>Newm</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_1.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_2.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_3.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_4.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_5.png)|

</details>

### Videos

| Sway | Wayfire | River | Hyprland | Newm |
| --- | --- | --- | --- | --- |
|[![Sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_4.png)](https://youtu.be/ASlQcf8Jc0I)|[![Wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_4.png)](https://youtube.com/playlist?list=PLXH9dADRlWHYk_5Boqiu7L3HcLVC83TWU)|[![River](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_4.png)](https://youtu.be/MwnK6arB2Rc)|[![Hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_4.png)](https://youtu.be/t6Zd2F7rtPw)|[![Newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_5.png)](https://youtube.com/playlist?list=PLXH9dADRlWHaXM3Q8G_gaunljITif3cUl)|

---

- For **Keybindings**, See `Help and Tips` app.
- I Hope you'll enjoy this flavor of Archcraft.
- Thank you for supporting Archcraft.
