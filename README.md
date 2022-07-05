# Hackintosh OpenCore EFI

## CONFIG
* OpenCore 0.8.1 RELEASE
* Intel HD 630
* ASUS B250M-A
* i7-7700
* WD_BLACK SN750 SE 500GB
* Realtek PCIe GbE Family Controller
* Realtek ALC887

## 安装
第一次安装如果跑代码后黑屏请把显卡设备id设置为12345678进行安装(使用config_12345678.plist重命名后安装)

安装成功再把显卡设备id改回12590000

## 异常处理
如果出现紫屏请参考网上教程

如果出现颜色异常,类似于反色但不完全是请尝试更改机型进行尝试（目前是i7-8700的机型）

如果HDMI点不亮,但DP可以点亮,如果是核显请尝试定制核显,如果是独显请尝试解决驱动的问题

其他问题请参考其他教程
