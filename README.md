简体中文 | [English](./README.en-US.md)

# 关于这个固件

> 这个仓库基于[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

用Github Actions为K2P自动编译固件

## 特性

* SSRPlus
* Turbo ACC
* Argon主题
* 广告过滤插件
* 可自定义软件包

## 用法

1. 上传自己的.config文件
2. 进入Actions页面手动启动编译
3. 当编译完成后，在Actions页面的右上角，点击Artifacts按钮下载含编译出的固件的压缩包
4. 进入breed，选择⚠️斐讯布局⚠️刷入压缩包中含sysupgrade字样的文件
5. | 项目 | 值 |
   | :--- | :--- |
   | 默认后台地址 | `192.168.2.1` |
   | 默认后台密码 | `password` |

## 教程 <a id="tutorial"></a>

* [如何安装固件](tutorial/how-to-install-the-firmware.md)
* [如何更新固件](tutorial/ru-he-geng-xin-gu-jian.md)
* [如何安装软件包](tutorial/how-to-install-custom-packages.md)

## 截图

![luci\_admin\_status\_overview](https://i.loli.net/2021/03/18/CXhbSEY2qG1gT4B.png)

## 注意
* Redmi K30 Ultra等MTK天玑1000+设备(不知道其它天玑设备有没有被波及)可能只有433Mbps(至少本人手机是这样)，目前尚未查明原因，如果知道原因，欢迎提issue。

![K30U\_Issues](https://i.loli.net/2021/03/18/TsXa75gWvLr3wOI.jpg)
