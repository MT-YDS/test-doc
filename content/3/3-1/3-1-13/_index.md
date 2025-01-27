---
title: 3.1.13. Power light/Reset switch
date: 2025-01-27T10:44:34+09:00
draft: true
weight: 130
---

![Connector_LED](images/LED_300x300.png)
![Connector_RESET](images/RESET_300x300.png)

#### Specifications
* POWER: オレンジランプ、READY: 緑ランプ。
* リセットスイッチ:タクタイルスイッチ

#### 使用上の注意点
Kakipに電源が接続されるとPOWERが点灯し、V2Hへ電源が投入されるとREADYが点灯します。
READYは電源エラー検出時またはリセットスイッチ押下時は消灯します。
リセットスイッチ及びJTAGコネクタのリセットは、常にコールドブートになります。
