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
- [Create A Bootable USB With Archcraft](https://wiki.archcraft.io/docs/boot-iso/boot-with-usb)
- [Boot Archcraft ISO With GRUB2 Bootloader](https://wiki.archcraft.io/docs/boot-iso/boot-with-grub)

### Overview
This special edition of Archcraft comes with [`Sway`](https://github.com/archcraft-os/archcraft-sway), [`Wayfire`](https://github.com/archcraft-os/archcraft-wayfire), [`River`](https://github.com/archcraft-os/archcraft-river), [`Hyprland`](https://github.com/archcraft-os/archcraft-hyprland) and [`Newm`](https://github.com/archcraft-os/archcraft-newm) pre-installed, pre-configured and provides you a wayland only Linux experience.

**ISO Generation :** `October 20th, 2022` <br>
**Last Updated :** `October 20th, 2022`

#### Changelog :
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

### Get The ISO

You can download the latest `ISO` from [ko-fi :coffee:](https://ko-fi.com/s/213becbf00).

> Default `username` and `password` is **liveuser**.


---

For Installation Instructions, See [Install Archcraft With Calamares](https://wiki.archcraft.io/docs/install-archcraft/install-with-calamares)

**`NOTE :`** If you want to try this ISO in ***Virtualbox***, Make sure you use `VMSVGA` as Graphics Controller and Check `Enable 3D Acceleration` box. If the cursor is not visible, Add `export WLR_NO_HARDWARE_CURSORS=1` in your `~/.profile` file. 

**More info :** [No mouse cursor visible on VirtualBox](https://github.com/swaywm/sway/issues/3814)

#
<br>

**`WARNING :`** This ISO may or may not work with `Nvidia` (*using proprietary graphics drivers*)

**More info :** [Sway Installation](https://wiki.archlinux.org/title/Sway#Installation), [wayland Requirements](https://wiki.archlinux.org/title/wayland#Requirements)

---

### Screenshots

<!-- Sway -->

<details>
<summary><b>Sway</b></summary>

| App Launcher (wofi) | Terminal (foot) | Tile Mode | Floating Mode |
| --- | --- | --- | --- |
|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_1.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_2.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_3.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_4.png)|

| Running thunar, geany and ranger | Running vim, ncmpcpp and ranger | Another tile mode | Wlogout |
| --- | --- | --- | --- |
|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_5.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_6.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_7.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_8.png)|

</details>

<!-- Wayfire -->

<details>
<summary><b>Wayfire</b></summary>

| Wayfire |
| --- |
|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshot.png)|

</details>

<!-- River -->

<details>
<summary><b>River</b></summary>

| App Launcher (wofi) | Powermenu (wofi applet) | Terminal (foot) | Floating Mode (thunar, geany, fetch) |
| --- | --- | --- | --- |
|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_1.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_2.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_3.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_4.png)|

| Tile Layout 1 | Tile Layout 2 | Tile Layout 3 | Tile Layout 4 |
| --- | --- | --- | --- |
|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_5.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_6.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_7.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_8.png)|

</details>

<!-- Hyprland -->

<details>
<summary><b>Hyprland</b></summary>

| Desktop (wofi) | Floating | Tiled | Thunar, Geany | Wlogout |
| --- | --- | --- | --- | --- |
|![hypr](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_dark_1.png)|![hypr](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_dark_2.png)|![hypr](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_dark_3.png)|![hypr](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_dark_4.png)|![hypr](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_dark_5.png)|

</details>

<!-- NEWM -->

<details>
<summary><b>Newm</b></summary>

| Desktop | Tiles | Wofi |
| --- | --- | --- |
|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_1.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_2.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_3.png)|

| Lockscreen | Overview | Wlogout |
| --- | --- | --- |
|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_4.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_5.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_6.png)|

</details>

### Videos

| Sway | Wayfire | River | Hyprland | Newm |
| --- | --- | --- | --- | --- |
|[![Sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_6.png)](https://youtu.be/ASlQcf8Jc0I)|[![Wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshot.png)](https://youtube.com/playlist?list=PLXH9dADRlWHYk_5Boqiu7L3HcLVC83TWU)|[![River](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/River_4.png)](https://youtu.be/MwnK6arB2Rc)|[![Hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_dark_2.png)](https://youtu.be/t6Zd2F7rtPw)|[![Newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/solid/newm_5.png)](https://youtube.com/playlist?list=PLXH9dADRlWHaXM3Q8G_gaunljITif3cUl)|

---

- I Hope you'll enjoy this flavor of Archcraft.
- Thank you for supporting Archcraft.
