# Hackintosh-EVGA Dark X299-I9 7980XE-RX580｜Sequoia15.0.1（Opencore 1.0.2）
---
这是一个EVGA Dark X299主板+7980XE的OC黑苹果配置文件。


| Sequoia 15.0 beta2                                           |Sequoia 15.0(24A335)                                                 | Sequoia 15.0.1(24A348)                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![截屏2024-06-26 18 33 23](https://github.com/longlongdede/Hackintosh-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/d3d24267-6bb2-48b9-b628-1c9b26234be4) |![截屏2024-09-24 09 22 44](https://github.com/user-attachments/assets/2384d92f-8342-4ef5-b6fa-8c9c51826e4c) | ![截屏2024-10-11 21 02 17](https://github.com/user-attachments/assets/3a1187b0-b198-4eb2-9b15-0e4bad5e9f2a)
 |

---
## 更新

| 日期 | MacOS版本 | Opencore版本 |
|---|---|---|
| 2024-02-22 | Sonoma 14.3.1 | 0.9.8 |
| 2024-03-14 | Sonoma 14.4 | 0.9.9 |
| 2024-03-28 | Sonoma 14.4.1 | 0.9.9|
| 2024-04-22 | Sonoma 14.4.1 | 1.0.0开发版|
| 2024-05-11 | Sonoma 14.4.1 | 1.0.0|
| 2024-05-14 | Sonoma 14.5 | 1.0.0|
| 2024-06-26 | sequoia 15 beta2 | 1.0.0|
| 2024-09-24 | sequoia 15 正式版 | 1.0.1|
| 2024-10-11 | sequoia 15.0.1 正式版 | 1.0.2|


---
## 硬件配置
- BIOS版本：1.29（2021-12-01）
- 主板：EVGA Dark X299
- 处理器：I9-7980XE
- 内存：Asgard 洛极T2 DDR4 2666MHz 32G✖️4
- 显卡：MSI RX580 8G 2304sp
- 散热器：利民 AE 360 ARGB
- 硬盘：大华 C900Plus
- 电源：矿龙1150W
- 无线网卡：Intel AX210NGW
---
## BIOS设置
1. ADVANCED->CPU Configuration->MSR Lock Control:Disabled
2. ADVANCED->CPU Configuration->Intel(R) Virtualization Technology For Directed I/0:Disabled
3. ADVANCED->PCle Configuration->Above 4G Decoding:Enabled
4. ADVANCED->PCle Configuration->Re-Size BAR Support:Enabled
5. ADVANCED->SATA Configuration->SATA Mode Selection:AHCI
6. BOOT->Fast Boot:OFF
7. BOOT->CSM Configuration->CSM Support:Disabled
8. BOOT->Secure Boot:Disabled
9. BOOT->Secure Boot->Secure Boot Mode:Custom
10. BOOT->Secure Boot->Key Management-> Delete all Secure Boot variables（如果这项不可选中，确保此页面下方所有 key 都显示 0 和 No Key）

---
## 完美程度
- RX580正常驱动，DP和HDMI输出正常，分辨率正常。
- 传感器工作正常，CPU温度、睿频，硬盘信息、温度，风扇转速正常
- USB2.0和USB3.0速度正常，TYPE-C速度正常。
- 双口有线网卡正常
- AX210无线网卡和蓝牙不能驱动
- 睡眠正常，唤醒正常。
- 隔空投送可以搜到设备，但是不能发送。其他设备搜不到本机。
---
## Enjoy It
![2024-02-22_22-11-13](https://github.com/longlongdede/Hakintoshi-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/95ed92c2-1d35-48ad-9a97-696c1f7ba2e3)

![截屏2024-05-14 09 56 31](https://github.com/longlongdede/Hackintosh-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/99d12c44-ef01-47b3-a397-807c1d278be0)

![2024-02-22_22-09-25](https://github.com/longlongdede/Hakintoshi-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/761b7886-547a-4d5c-a438-61502a0ebaed)

![](https://wqong.oss-cn-hangzhou.aliyuncs.com/test/2024-04-23_06-58-37.png)

