# 华硕飞行堡垒第 5 代 (FX-504GE)
### 注意：如果你弄乱了我的指南，我不会对任何问题负责。
#### 请不要使用蓝牙的 Kexts （目前依然不支持 MacOS 蒙特雷）

![Screenshot 2021-06-13 at 12 41 31 PM](https://user-images.githubusercontent.com/85815874/121795795-971d7800-cc46-11eb-9afa-556592a81087.png)
                                      ** 我的桌面和我的 Mac **
                          
## 语言
- 英语
- 华语 (简体)

## 硬件 (我的配置)
- CPU (处理器) : Intel Core i5-8300H CoffeeLake 8th
- GPU (内置显卡) : Intel Graphics UHD630
- dGPU (独立显卡) : Nvidia GTX1050Ti (4GB GDDR5 VRAM)
- 内存 : DDR4 12GB 2400MHz
- 存储 : 1TB HDD + 256GB SSD
- 荧幕 : 15.6" Full HD 60Hz (1920 x 1080) 
- 音板 : Realtek ALC255
- WIFI / 蓝牙 : Intel Wireless AC9560
- BIOS 系统 : Dualboot MacOS Monterey + Windows 10
- 触摸板 : ELAN I2C

## 什么是运作的 ?
- [x] 禁用独立显卡只用内置显卡
- [x] WiFi (100% 运作) / 以太网 (我没尝试，但我认为有在工作)
- [x] 音频/麦克风 输入, 输出 (100 % 运作当使用最新的 Opencore EFI)
- [x] 耳机插孔 (Youtube 上只有背景声微人声 ，但在内置视频没问题)
- [x] ACPI 荧幕显示亮度与热键 / 滑块
- [x] 电源管理
- [x] 睡眠与唤醒 
- [x] 网络摄像头
- [x] 3 个 Usb 3.1 & HDMI 端口 (HDMI 运作当使用最新的 Opencore EFI)
- [x] Fn 键支持本机热键
- [x] 触摸板和手势 (在最新的恶 OpenCore EFI. 可用) 
- [x] 带 USB 网络分享的热点 (在最新的恶 OpenCore EFI. 可用) 
- [x] 系统更新


## 无法运作
- Nvidia GTX1050Ti (不支持)
- 蓝牙 (等待新的 kext 兼容 MacOS 蒙特雷 , 输入最新的 kext 兼容其他的 MacOS)

## 政治处理和测试工作 & 修复问题列表
- 耳机插孔
- 睡眠与唤醒 (睡死的状态当在睡眠的状态)
- 网络摄像头 (当睡眠并睡醒后不工作)
- AppleTV , AppleMusic 和其他 (DRM 问题)

## 基分 / 跑分
![Screenshot 2021-06-13 at 12 52 06 PM](https://user-images.githubusercontent.com/85815874/121795848-0f843900-cc47-11eb-8b66-eff358a82c7d.png)

## 资料来源于
- 特别感谢 Acidanthera 提供大部分的 Kexts。
- 感谢 OpenCore 引导加载程序。
- 感谢 daliansky 提供 Airportitlwm 和蓝牙 kext。
- 感谢 alexandred 提供 VoodooI2C。
- 感谢 RehabMan 提供 ACPI 修补指南。
- 感谢 hackintosh-stuff 对 ALC255 的 ComboJack 支持。
- 感谢面子书社群名为 "Hackintosh" , "我和我的黑苹果“。

## 最后一件事 ..
- 我很高兴社区可以帮助我们解决无法工作的问题 !! 
- 如果解决了任何问题，请给我发封电子邮件以帮助我更新 GITHUB 中的文件夹。

