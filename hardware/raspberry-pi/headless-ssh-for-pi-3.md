# Headless SSH for Pi 3

This guide assumes you've already got some unix based system flashed to your SD card and that you are running MacOS.

First, create a file 'ssh' in the flashed sd card to enable ssh.

```text
touch /Volumes/boot/ssh
```

Now we create a wpa\_supplicant.conf for our wifi details

```text
vi /Volumes/boot/wpa_supplicant.conf
```

And hit 'i' for insert mode and add the following replacing 'WIFINAME' and 'WIFIPASSWORD' with the appropriate values

```text
country=US
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1

network={
    ssid="WIFINAME"
    psk="WIFIPASSWORD"
}

```



