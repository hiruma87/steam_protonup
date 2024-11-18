# steam_protonup
## Steam
### Install steam
   **Arch Linux**
   ```bash
   sudo pacman -S steam
   ```
   **Debian**
   ```bash
   sudo apt install steam
   ```
   > You can also download the .deb file from steam page [Steam Store](https://store.steampowered.com/about/)
   **Fedora**
   ```bash
   sudo dnf install steam
   ```
### Setting up steam
1. Run the newly installed steam
2. Login
3. Exit steam
> The reason for above steps so that steam will create a .steam folder at $HOME folder
___
## Setting up proton-GE
### Install protonup-qt
- Easiest way to install protonup for steam is via protonup-qt
- The advantage of this apps, you can also get another wine fork besides proton-GE
- You can also install proton in lutris (a game launcher)

**Install Flatpak**

**Arch Linux**

Install flatpak by
```bash
sudo pacman -S flatpak
```
> May need a reboot
___
**Debian**

Install flatpak by
```bash
sudo apt install flatpak
```
Install plugin
For gnome user
```bash
sudo apt install gnome-software-plugin-flatpak
```
For KDE user
```bash
sudo apt install plasma-discover-backend-flatpak
```
Lastly add flatpak repository
```bash
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```
___
**Fedora**
