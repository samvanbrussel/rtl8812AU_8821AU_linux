# Realtek 8812AU/8821AU USB WiFi driver

## Known Supported Devices

* D-Link Wireless AC600 Dual Band High-Gain USB Adapter (Model: DWA-172)
* COMFAST 1200Mbps USB Wireless Adapter (Model: CF-912AC)
* TP-LINK AC1200 Wireless Dual Band USB Adapter (Model: Archer-T4U)

## Compiling for Raspberry Pi

```sh
sudo apt-get install git build-essential raspberrypi-kernel-headers -y
git clone https://github.com/samvanbrussel/rtl8812AU_8821AU_linux.git
cd rtl8812AU_8821AU_linux
make
sudo make install
sudo modprobe rtl8812au
```
