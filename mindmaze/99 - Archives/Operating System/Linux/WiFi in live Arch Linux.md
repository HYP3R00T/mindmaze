# WiFi in Live [[Arch Linux]]

The challenge I faced while installing Arch Linux in a laptop is the very first step of connecting to a network.  
The [Arch wiki for iwd](https://wiki.archlinux.org/title/iwd) is excellent, but it is missing a small troubleshooting message. 

Even after scanning your device using `station wlan0 scan`, if the list of available networks (`station wlan0 get-networks`) is blank, then do the following.

- Exit out of the `iwctl` instance.
- Start `iwd.service`

```shell
systemctl start iwd.service
```

- Enter into `iwctl` and restart the device.

```shell
device wlan0 set-property Powered off
device wlan0 set-property Powered on
```

---

**Ref:**
- https://joshtronic.com/2021/11/21/connecting-to-wifi-with-iwd/
