# About this firmware 

> This repository is based on [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt) and [DreamWalkerXZ/Actions-OpenWrt](https://github.com/DreamWalkerXZ/Actions-OpenWrt-K2P)

Use Github Actions Automatically compile firmware for K2P 

## Feature

* SSRPlus
* Turbo ACC
* Argon Theme
* Ad filter
* Customizable software package

## Usage

1. Upload your own `.config` file 
2. Enter the Actions page to manually start the compilation
3. When the compilation is complete, in the upper right corner of the Actions page, click the Artifacts button or the WeTransfer link in Annotations to download the compressed package containing the compiled firmware
4. Enter breed and select ⚠️Phicomm layout⚠️ to brush into the file containing the word `sysupgrade` in the compressed package 
5. | project | value |
   | :--- | :--- |
   | Default address | `192.168.2.1` |
   | Default password | `password` |

## 截图

![luci\_admin\_status\_overview](https://i.loli.net/2021/03/18/CXhbSEY2qG1gT4B.png)

## 注意
* Redmi K30 Ultra and other MTK Dimensity 1000+ devices (I don’t know if other Dimensity devices are affected) may only have 433Mbps (at least my mobile phone is like this). The reason has not been found yet. If you know the reason, please submit an issue. 

![K30U\_Issues](https://i.loli.net/2021/03/18/TsXa75gWvLr3wOI.jpg)
