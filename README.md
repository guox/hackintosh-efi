# 10th Intel and 17th AMD Hackintosh EFI

My hackintosh [OpenCore](https://github.com/acidanthera/OpenCorePkg) EFI for 17th AMD and 10th Intel.

支持10代Intel/锐龙三代AMD和华硕主板，OpenCore的配置主要以官网为主。理论上如果你的CPU/主板和我的一样或者同品牌同系列，应该99%可以使用，剩下的1%就看运气了。

EFI仅支持你能够成功安装并解决了一些小问题，安装成功后请参考[这里](https://dortania.github.io/OpenCore-Post-Install/)自行进行一些扫尾工作。

## 10th Intel and ASUS B460

### Hardware

* Intel i5-10500
* ASUS TUF GAMING B460M-PLUS (WI-FI) 
* Intel UHD 630
* Gloway TYPE-α 16GB
* UNIC P5160 512GB
* Fenvi T919

### macOS version

10.15.16

### Opencore version

0.5.9

### What works

* Fix F1 bios problem when start
* UHD 630 @ Dell U2720Q 4K 60hz
* Audio
* LAN
* Wi-Fi (via Fenvi T919)
* Bluetooth (via Fenvi T919)

### What doesn't works

* HDMI (technically this issue can be fixed, but I don't need it, so...)

