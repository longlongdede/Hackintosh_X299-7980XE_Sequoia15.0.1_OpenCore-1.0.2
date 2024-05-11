# Hackintosh-EVGA Dark X299-I9 7980XE-RX580
---
这是一个EVGA Dark X299主板+7980XE的OC黑苹果配置文件。


| ![2024-02-22_22-13-49](https://github.com/longlongdede/Hakintoshi-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/8519602f-d878-4f18-839c-3845bc0d2ae2) | ![2024-04-23_06-59-41](https://github.com/longlongdede/Hackintosh-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/7ac25a51-8898-4a77-97fe-77206fdc0ca6) | 
|---|---|

---
## 更新

| 日期 | MacOS版本 | Opencore版本 |
|---|---|---|
| 2024-02-22 | Sonoma 14.3.1 | 0.9.8 |
| 2024-03-14 | Sonoma 14.4 | 0.9.9 |
| 2024-03-28 | Sonoma 14.4.1 | 0.9.9|
| 2024-04-22 | Sonoma 14.4.1 | 1.0.0|


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
- AX200无线网卡正常，蓝牙正常
- 睡眠正常，唤醒正常。
- 隔空投送可以搜到设备，但是不能发送。其他设备搜不到本机。
- 增加板载AX210网卡，大多数情况下不能驱动，偶尔可以。

---
## Enjoy It
![2024-02-22_22-11-13](https://github.com/longlongdede/Hakintoshi-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/95ed92c2-1d35-48ad-9a97-696c1f7ba2e3)

![2024-02-22_22-09-25](https://github.com/longlongdede/Hakintoshi-EVGA-Dark-X299-I9-7980XE-RX580/assets/63046146/761b7886-547a-4d5c-a438-61502a0ebaed)

![](https://wqong.oss-cn-hangzhou.aliyuncs.com/test/2024-04-23_06-58-37.png)

