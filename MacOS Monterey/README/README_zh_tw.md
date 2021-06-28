# 華碩飞行堡垒（TUF-FX504GE）
### 注意：如果你弄亂了我的指南，我不會對任何問題負責。
#### 其他MacOS使用原裝藍牙（BLinjector，BLfirmware）kext，MacOS Monterey藍牙kext臨時解決方案（Alpha版）。

![截圖 2021-06-13 at 12 41 31 PM](https://user-images.githubusercontent.com/85815874/121795795-971d7800-cc46-11eb-9afa-556592a81087.png)
                                      ** 我的桌面與關於這台 Mac **
                                      
用其他語言閱讀：[英文](README.md) , [馬來文](RRADME_mly.md) , [簡體中文](README_zh_cn.md) , [繁體中文](README_zh-tw.md)

## 硬件（我的規格）
- CPU（處理器）：Intel Core i5-8300H CoffeeLake 8th
- GPU（內置顯卡）：Intel Graphics UHD630
- dGPU（外置顯卡）：Nvidia GTX1050Ti（4GB GDDR5 VRAM）
- 內存：DDR4 12GB 2400MHz
- 存儲：1TB HDD + 256GB SSD
- 屏幕：15.6" 全高清 60Hz (1920 x 1080)
- 音板：Realtek ALC255
- WIFI / 藍牙：英特爾無線 AC9560
- BIOS 系統：雙啟動 MacOS Monterey + Windows 10
- 觸摸板：ELAN I2C

## 什麼在起作用 ？
- [x] 禁用 dGPU 的 iGPU
- [x] WiFi（100% 工作）/以太網（我沒有嘗試，但我認為它工作正常）
- [x] 藍牙（kext 僅適用於 Monterey） 
- [x] 音頻/麥克風輸入、輸出（100% 使用最新的 Opencore EFI）
- [x] 耳機插孔（Youtube 上有聲音，但內部視頻工作正常）
- [x] ACPI 顯示亮度與熱鍵/滑塊
- [x] 電池管理
- [x] 睡眠與喚醒
- [x] 網絡攝像頭
- [x] 3 個 USB 3.1 和 HDMI 端口（HDMI 在最新的 Opencore EFI 中工作）
- [x] Fn 鍵支持本機熱鍵
- [x] 觸摸板和手勢（在最新的 OpenCore EFI 中可用）
- [x] 帶 USB 網絡共享的熱點（在最新的 OpenCore EFI 中可用）
- [x] 系統更新

## 不工作
- Nvidia GTX1050Ti（不支持）

## 正在處理測試工作並修復問題列表
- 耳機插孔
- 睡眠和喚醒（睡眠時間過長時的睡眠死亡問題）
- 網絡攝像頭（睡眠後不工作）
- AppleTV、AppleMusic 等（DRM 問題）

## 跑分
![截圖 2021-06-13 at 12 52 06 PM](https://user-images.githubusercontent.com/85815874/121795848-0f843900-cc47-11eb-8b66-eff358a82c7d.png)

## 資料來源於
- 特別感謝 Acidanthera 提供了大部分 Kext。
- 感謝 OpenCore 引導加載程序。
- 感謝 daliansky 提供 Airportitlwm 和藍牙 kext。
- 感謝 alexandred 的 VoodooI2C。
- 感謝 RehabMan 提供 ACPI 修補指南。
- 感謝 hackintosh-stuff 對 ALC255 的 ComboJack 支持。
- 感謝名為“Hackintosh”、“我和我的黑蘋果”的 Facebook 社群。

## 最後一件事 ..
- 我很高興社區可以幫助我們解決無法工作的問題！！
- 如果解決了任何問題，請給我發封電子郵件以幫助我更新 GITHUB 中的文件夾。
