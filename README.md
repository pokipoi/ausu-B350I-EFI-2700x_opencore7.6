# B350I-EFI-opencore
### 概览
  B350I EFI opencore6.4 catalina
  | Hardware | Model |
  |----------|-------|
  | 电脑型号 | X64 兼容 台式电脑 |
  | 操作系统 |Windows 10 专业版 64位（Version 2009 / DirectX 12）|
  | 处理器 |AMD Ryzen 7 2700X Eight-Core 八核 |  
  | 主板 | 华硕 ROG STRIX B350-I GAMING（AMD PCI 标准主机 CPU 桥）|  
  | 显卡 | AMD Radeon RX Vega 64 ( 8 GB / AMD ) |  
  | 内存 | 16 GB ( 海盗船 DDR4 3200MHz )|  
  | 主硬盘 | 三星 SSD 960 EVO 250GB ( 250 GB / 固态硬盘 ) |  
  | 显示器 | 优派 VSC0F30 VA2261 ( 21.5 英寸  ) |  
  | 声卡 | 瑞昱  @ AMD High Definition Audio 控制器 | 
  | 网卡 | 英特尔 I211 Gigabit Network Connection / 华硕 |
  
 [详细配置](https://github.com/vsnotme/B350I-EFI-opencore/blob/main/%E8%AF%A6%E7%BB%86%E6%8A%A5%E8%A1%A8.txt)
 
 ##### 可用：
- 支持随航
- wifi，需要支持Wireless USB Adapter Clover的usb网卡（cf-811ac）之类
- 声音
##### 问题：
- ~~睡眠：当有usb插在蓝色的usb3.0上时，睡眠将崩溃。请插在红色的usb3.1上或者使用USBhub插在3.1上并将它内建。保持蓝色usb3.0为空的。~~
- 在Big Sur及monterey中发现处于AMD的系统已经没有了USB导致的睡眠问题。
 ### 要注意的点
-  #### 某些ssd硬盘会导致安装系统失败比如我的OCZ -VERTEX460A，解决办法是在一块机械硬盘上安装好系统用克隆工具克隆到ssd
-  #### 相信找到这里的小可爱肯定知道需要获取 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)生成新的 SMBIOS ID 吧
-  #### 安装旧版本系统会出现错误，解决办法在安装界面的终端更改时间：
   ```
   date 070512052018.03
   （date 月日时分年.秒）
   ```
 [终端修改时间](https://jingyan.baidu.com/article/d169e18614c996436611d83e.html)
 
  [免责声明](https://github.com/vsnotme/B350I-EFI-opencore/blob/main/%E5%85%8D%E8%B4%A3%E5%A3%B0%E6%98%8E.txt)
  
 ### 碰到的一些雷区
 #### 算是自己的一些总结，把遇到的问题捋一捋
 -  ###
