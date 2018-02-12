# Modprobe files

These files will load the video4linux loopback kernel module at startup. Copy the `v4l2loopback.conf` file from each directory into the corresponding directory inside `/etc`, ie

```term
cp homebridge-octocam/modprobe/modules-load.d/v4l2loopback.conf /etc/modules-load.d
cp homebridge-octocam/modprobe/modprobe.d/v4l2loopback.conf /etc/modprobe.d
```
