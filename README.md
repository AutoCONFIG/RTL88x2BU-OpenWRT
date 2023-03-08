# RTL88x2BU-OpenWRT
## 请不要再关注此仓库，此仓库属于调试性质，并不能工作。
## Please don't STAR, it's DEBUG repository,it can't work.

适用于RTL88x2BU USB WiFi适配器的Linux/OpenWrt驱动

支持的设备包括但不限于如下：
* ALFA AWUS036ACU
* ASUS AC1300 USB-AC55 B1
* ASUS AC53 Nano
* ASUS U2
* Cudy WU1400
* Edimax EW-7822UAD
* Edimax EW-7822ULC
* Edimax EW-7822UTC
* EDUP EP-AC1605GS
* FIDECO 6B21-AC1200M
* Linksys WUSB6300 V2
* NetGear A6150
* TRENDnet TEW-808UBM
* Numerous additional products that are based on the supported chipsets

### Linux/OpenWrt编译方法:
```bash
clone the repository to "openwrt-src/package" dir:
git clone https://github.com/AutoCONFIG/RTL88x2BU-OpenWRT.git
cd "openwrt-src" dir
make menuconfig
select "> Kernel modules > Wireless Drivers > kmod-rtl88x2bu"
make V=s
```
