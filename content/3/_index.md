---
title: 3 ハードウェアについて
date: 2024-10-07T03:19:00+09:00
draft: false
weight: 30
---

## Kakipのハードウェア概要
### AI-MPU（主な仕様のみ）
**Renesas RZ/V2H (R9A09G057H48GBG)**<br>

|項目|仕様|
|:---|:---|
|CPU|Cortex-A55 Quad 1.1GHz <br> Cortex-R8 Dual 800MHz <br> Cortex-M33 200MHz|
|NPU|DRP-AI3 (Hardware AI Accelerator) <br> DRP (Vision/Dynamics Accelerator)|
|Video Codec|H.265、H.264エンコード・デコード（4K 30fps）|
|Option|Mali-G31: 3D Graphics <br> Mali-C55: ISP <br> Security IP搭載|

***
### その他カタログ仕様

|項目|仕様|
|:---|:---|
|Memory|LPDDR4 (2GB/4GB/8GB) <br> 初ロットでの生産は8GBのみ。2GB/4GBは市場ニーズを見て投入。|
|Video In|MIPI-CSI2 4Lane x 4ch (22pin FFC)|
|Video Out|MIPI-DSI 4Lane x 1ch (22pin FFC)|
|Ethernet|10Base-T/100Base-TX/1000Base-T (RJ45)|
|USB|USB3.2 Gen1 Type-A x 2port <br> USB2.0 FS Type-C x 1port|
|CAN-FD|CAN-FD x 2ch (Connector: ZH-3P: S3B-ZR-SM4A-TF)
|PCIe|PCI Express (Gen3x4) x1ch (16pinFFC) EndPoint|
|GPIO|40pin 2.54mm pitch pin-header|
|Boot Media|microSD Card (Minimum 16GB)|
|Power Supply|DC9-24V/25W (DC Jack φ5.5mm/φ2.1mm)|
|Dimensions|L85mm x W56mm x H19mm（突起部除く）|
|Weight|47g|
|OS|Ubuntu 24.04 (Kernel: Based on Yocto Linux in Renesas BSP)|
|保存温度|-15〜60度（結露なきこと）|
|推奨動作温度|0〜40度（結露なきこと）|
|Origin|Made In Japan|

***

