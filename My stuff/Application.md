### Tor Browser

##### openSUSE

```
sudo zypper in torbrowser-launcher torbrowser-apparmor-profile
```

### GitHub Desktop

##### openSUSE

First install our GPG certificate:

```
$ sudo rpm --import https://mirror.mwt.me/ghd/gpgkey
```

To setup the package repository, run one of these commands:

```
# if you want to use packagecloud.io
$ sudo sh -c 'echo -e "[shiftkey]\nname=GitHub Desktop\nbaseurl=https://packagecloud.io/shiftkey/desktop/el/7/\$basearch\nenabled=1\ngpgcheck=0\nrepo_gpgcheck=1\ngpgkey=https://mirror.mwt.me/ghd/gpgkey" > /etc/zypp/repos.d/shiftkey-desktop.repo'

# if you want to use the US mirror
$ sudo sh -c 'echo -e "[shiftkey]\nname=GitHub Desktop\nbaseurl=https://mirror.mwt.me/ghd/rpm\nenabled=1\ngpgcheck=0\nrepo_gpgcheck=1\ngpgkey=https://mirror.mwt.me/ghd/gpgkey" > /etc/zypp/repos.d/shiftkey-desktop.repo'
```

Then install GitHub Desktop:

```
# if zypper is your package manager
$ sudo zypper ref && sudo zypper in github-desktop
```

### Davinci Resolve (Studio) 18 Audio delay fix

```
sudo zypper in alsa-plugins-pulse alsa-plugins-pulse-32bit
```

### GIMP

```
sudo zypper in gimp gimp-plugin-gmic gimp-plugin-resynthesizer
```
