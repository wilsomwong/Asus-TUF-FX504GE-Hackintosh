# Asus-TUF-FX504GE
### CATATAN: SAYA TIDAK BERTANGGUNGJAWAB UNTUK SEBARANG MASALAH JIKA ANDA MENGESAN PANDUAN SAYA.
#### Jangan Gunakan kext Bluetooth (Masih belum serasi untuk MacOS Monterey)

![Screenshot 2021-06-13 at 12 41 31 PM](https://user-images.githubusercontent.com/85815874/121795795-971d7800-cc46-11eb-9afa-556592a81087.png)
                                      ** Dekstop Saya dengan Mengenai Mac Ini **
                                      
Baca ini dalam bahasa lain: [Bahasa Inggeris](README.md), [Bahasa Melayu](README_mly.md) , [Bahasa Cina (Ringkas)](README_zh_cn.md) , [Bahasa Cina (Tradisional)](README_zh_tw.md)

## Perkakasan (Spesifikasi Saya)
- CPU (Pemproses): Intel Core i5-8300H CoffeeLake 8th
- GPU (Kad Grafik Dalaman): Intel Graphics UHD630
- dGPU (Kad Grafik Luaran): Nvidia GTX1050Ti (4GB GDDR5 VRAM)
- RAM: DDR4 12GB 2400MHz
- Storan: 1TB HDD + 256GB SSD
- Skrin: 15.6 "Full HD 60Hz (1920 x 1080)
- SoundBoard: Realtek ALC255
- WIFI / Bluetooth: Intel Wireless AC9560
- Sistem BIOS: Dualboot MacOS Monterey + Windows 10
- Pad sentuh: ELAN I2C

## Apa Yang Berfungsi?
- [x] iGPU dengan dGPU yang dilumpuhkan
- [x] WiFi (100% Bekerja) / Ethernet (Saya tidak mencuba tetapi saya rasa ia berfungsi)
- [x] Input Audio / Mic, Output (100% berfungsi pada EFI Opencore terakhir)
- [x] Jack Headphone (bunyi retak di Youtube tetapi video dalaman berfungsi dengan baik)
- [x] Kecerahan paparan ACPI dengan butang panas / gelangsar
- [x] Pengurusan Bateri
- [x] Tidur & Bangun
- [x] Kamera Web
- [x] 3 port Usb 3.1 & HDMI port (HDMI berfungsi dalam OpenCore EFI terkini)
- [x] Sokongan hotkey asli dengan kekunci Fn
- [x] Pad sentuh dan gerak isyarat (Terdapat dalam EFI OpenCore terakhir)
- [x] Hotspot dengan Penambatan USB (Terdapat dalam EFI OpenCore terakhir)
- [x] Kemas kini Sistem

## Tidak bekerja
- Nvidia GTX1050Ti (Tidak disangka)
- Bluetooth (Tunggu sahaja kext baru ke MacOS Monterey yang serasi, masukan kext bluetooth terbaru yang sesuai untuk MacOS lain)

## Dalam proses untuk ujian berfungsi & Perbaiki senarai masalah
- Jack Headphone
- Tidur & Bangun (Masalah Kematian Tidur ketika tidur terlalu lama)
- WebCam (Tidak Bekerja selepas tidur)
- AppleTV, Apple Music dan lain-lain (masalah DRM)

## BenchMark
![Screenshot 2021-06-13 at 12 52 06 PM](https://user-images.githubusercontent.com/85815874/121795848-0f843900-cc47-11eb-8b66-eff358a82c7d.png)

## Kredit
- Terima kasih khas kepada Acidanthera untuk sebilangan besar Kexts.
- Terima kasih kepada OpenCore Bootloader.
- Terima kasih kepada daliansky untuk Airportitlwm dan Bluetooth kext.
- Terima kasih kepada alexandred untuk VoodooI2C.
- Terima kasih kepada RehabMan untuk panduan tampalan ACPI.
- Terima kasih kepada hackintosh-stuff untuk sokongan ComboJack untuk ALC255.
- Terima kasih kepada Halaman Facebook yang disebut "Hackintosh", "我 和 我 的 黑 苹果".

## Perkara Terakhir ..
- Saya gembira kerana komuniti dapat membantu kami menyelesaikan masalah yang tidak dapat dilaksanakan !!
- Sekiranya ada masalah yang diselesaikan, sila masukkan e-mel kepada saya untuk membantu saya mengemas kini folder saya di GITHUB.
