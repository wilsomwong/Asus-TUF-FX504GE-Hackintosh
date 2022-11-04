# 华硕-TUF-FX504GE
### 注意：如果你弄乱了我的指南，我不会对任何问题负责。
#### 其他MacOS使用原装蓝牙（BLinjector，BLfirmware）kext，MacOS Monterey蓝牙kext暂时只解决（Alpha版）。

![截图 2021-06-13 at 12 41 31 PM](https://user-images.githubusercontent.com/85815874/121795795-971d7800-cc46-11eb-9afa-556592a81087.png)
                                      ** 我的桌面与关于这台 Mac **
                                      
用其他语言阅读：[English](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README.md) , [Malay](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README/README_mly.md ) , [中文（简体）](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README/README_zh_cn.md) , [中文（繁体）](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/blob/main/MacOS%20Monterey/README/README_zh_tw.md)
#### ** 其他语言更新信息会延迟。

## 硬件（我的规格）
- CPU（处理器）：Intel Core i5-8300H CoffeeLake 8th
- GPU（内置显卡）：Intel Graphics UHD630
- dGPU（外置显卡）：Nvidia GTX1050Ti（4GB GDDR5 VRAM）
- 内存：DDR4 12GB 2400MHz
- 存储：1TB HDD + 256GB SSD
- 屏幕：15.6" 全高清 60Hz (1920 x 1080)
- 音板：Realtek ALC255
- WIFI / 蓝牙：英特尔无线 AC9560
- BIOS 系统：双启动 MacOS Monterey + Windows 10
- 触摸板：ELAN I2C (HID)

## 什么在起作用？
- [x] 禁用 dGPU 的 iGPU
- [x] WiFi（100% 工作）/以太网（我没有尝试，但我认为它工作正常）
- [x] 蓝牙（kext 仅适用于 Monterey）
- [x] 音频/麦克风输入、输出（100% 使用最新的 Opencore EFI）
- [x] 3.5 毫米耳机插孔
- [x] ACPI 显示亮度与热键/滑块
- [x] 电池管理
- [x] 睡眠与唤醒
- [x] 网络摄像头
- [x] 3 个 USB 3.1 和 HDMI 端口（HDMI 在最新的 Opencore EFI 中工作）
- [x] Fn 键支持本机热键
- [x] 触摸板和手势（在最新的 OpenCore EFI 中可用）
- [x] 带 USB 网络共享的热点（在最新的 OpenCore EFI 中可用）
- [x] 系统更新

## 不工作
- Nvidia GTX1050Ti（不支持）

## 正在处理测试工作并修复问题列表
- [ ] 系统更新（有问题，稍后修复）
- [ ] 蓝牙（休眠后无法打开蓝牙，等稳定版出来..）
- [ ] 网络摄像头（睡眠后不工作）
- [ ] AppleTV、AppleMusic 等（DRM 问题，目前无解决方案）

## 基准
![截图 2021-06-13 at 12 52 06 PM](https://user-images.githubusercontent.com/85815874/121795848-0f843900-cc47-11eb-8b66-eff358a82c7d.png)

## 贡献 / 跑分
- 特别感谢 Acidanthera 提供了大部分 Kext。
- 感谢 OpenCore 引导加载程序。
- 感谢 daliansky 提供 Airportitlwm 和蓝牙 kext。
- 感谢亚历山大的 VoodooI2C。
- 感谢 RehabMan 提供 ACPI 修补指南。
- 感谢 hackintosh-stuff 对 ALC255 的 ComboJack 支持。
- 感谢名为“Hackintosh”、“我和我的黑苹果” 的 Facebook 页面。

## 最后一件事 ..
- 我很高兴社区可以帮助我们解决无法工作的问题！！
- 如果有任何问题解决了，请收件箱给我电子邮件，以帮助我更新 GITHUB 中的文件夹。
#
[![GitHub version](https://img.shields.io/badge/OpenCore-0.7.0(Monterey)-brightgreen)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/tree/main/MacOS%20Monterey/OpenCore%207.0%20EFI)
[![GitHub version](https://img.shields.io/badge/OpenCore-0.7.1(Monterey)-brightgreen)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/tree/main/MacOS%20Monterey/OpenCore%207.1%20EFI)
[![GitHub version](https://img.shields.io/badge/OpenCore-0.8.3(Ventura)-brightgreen)](https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh/tree/main/MacOS%20Ventura)
[![Gitter](https://badges.gitter.im/Hackintosh-for-Asus-TUF-FX504/community.svg)](https://gitter.im/Hackintosh-for-Asus-TUF-FX504/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
