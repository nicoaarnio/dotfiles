## NVIDIA (Proprietary drivers)

### openSUSE Tumbleweed

#### Add the Nvidia Repository

```
$ sudo zypper addrepo --refresh https://download.nvidia.com/opensuse/tumbleweed NVIDIA
```

```
$ sudo zypper ref
```
<br>

#### Install

```
$ sudo zypper se nvidia
```

```
$ sudo zypper install nvidia-compute-G06 nvidia-compute-G06-32bit nvidia-compute-utils-G06 nvidia-driver-G06-kmp-default nvidia-drivers-G06 nvidia-gl-G06 nvidia-gl-G06-32bit nvidia-utils-G06 nvidia-video-G06 nvidia-video-G06-32bit
```

```
$ sudo reboot
```
<br>

#### Change DPI settings

System Settings > Appearance > Fonts > Force font DPI: 96

```
$ sudo logout
```
