# 关于这个固件

> 这个仓库基于[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)和[DreamWalkerXZ/Actions-OpenWrt](https://github.com/DreamWalkerXZ/Actions-OpenWrt-K2P)

用Github Actions为K2P自动编译固件

## 特性

* SSRPlus
* Turbo ACC
* Argon主题
* 广告过滤插件
* 可自定义软件包

## 用法

1. 上传自己的`.config`文件
2. 进入Actions页面手动启动编译
3. 当编译完成后，在Actions页面的右上角，点击Artifacts按钮或者Annotations里面的WeTransfer链接下载含编译出的固件的压缩包
4. 进入breed，选择⚠️斐讯布局⚠️刷入压缩包中含`sysupgrade`字样的文件
5. | 项目 | 值 |
   | :--- | :--- |
   | 默认后台地址 | `192.168.2.1` |
   | 默认后台密码 | `password` |

## 截图

![luci\_admin\_status\_overview](https://i.loli.net/2021/03/18/CXhbSEY2qG1gT4B.png)

## 注意
* Redmi K30 Ultra等MTK天玑1000+设备(不知道其它天玑设备有没有被波及)只有433Mbps，目前尚未查明原因，如果知道原因，欢迎提issue 
![K30U\_Issues](https://i.loli.net/2021/03/18/TsXa75gWvLr3wOI.jpg)
