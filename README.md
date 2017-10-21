# RaspberryPI Headleass

Headless configuration for your *raspberry Pi*

## Instructions
1. Copy this repo into the *BOOT* partition
2. Edit the **wpa_supplicant.conf** file by entering your network SSID and password, like this:
```
network={
    ssid="YOUR_NETWORK_NAME_HERE"
    psk="YOUR_PASSWORD_HERE"
    id_str="home"
}
```
3. Insert the microSD card into the RaspberryPi and **enjoy**