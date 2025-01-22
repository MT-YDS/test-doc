---
title: 3.11 DIP-SW
date: 2024-10-18T14:01:42+09:00
draft: true
weight: 110
---

#### SW1の動作設定
|DIP#|Name|Position| Description|
|:---|:---|:---:|:---|
|1|BOOTSEL|ON|Cortex-A55からブート|
|||OFF|Cortex-A33からブート|
|2/3|MD BOOT|ON/ON|指定禁止|
|||OFF/ON|SCIFからブート(CM33, CA55)|
|||ON/OFF|SDカードからブート(CA55のみ)*|
|||OFF/OFF|QSPI-Flashからブート(CM33, CA55)*|
|4|DEBUG EN|ON|JTAGデバグモード|
|||OFF|ノーマルモード|

(*) 指定のストレージにブートイメージが無い場合はSCIFに移行