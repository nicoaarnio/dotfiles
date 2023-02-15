### Install Flatpak

##### openSUSE

Install Flatpak from the command line using Zypper:

```
sudo zypper install flatpak
```

### Add the Flathub repository

Flathub is the best place to get Flatpak apps. To enable it, run:

```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

### Restart

To complete setup, restart your system.