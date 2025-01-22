---
title: 2.1 Boot Mediaの構築
date: 2024-10-06T18:17:00+09:00
draft: false
weight: 10
---

## KakipのOSブートメディア作成手順

ユーザーが円滑に開発を始められるよう、Kakip向けに最適化されたLinuxベースのソフトウェアを提供しています。本項目ではKakipに付属する基本ソフトウェアパッケージ（OSおよびデバイスドライバ類）を取得し、ブートメディアを作成する手順を示します。


### ご用意いただくもの

* OSイメージをダウンロード可能なパソコン（microSDカードへの書き込みが可能であれば、OSはWindows、MAC、Linux問いません）


### Kakip OSイメージのダウンロード

kakipのOSイメージは以下のリンクより取得ください。（Zipファイルサイズ：約3GB）

[kakip_os_image_v5 (2024.10.01)](https://www.kakip.ai/software/)


### microSDカードへの展開

imgファイルのメディアへの展開ツールは何種類かありますが、ここではbalenaの「Etcher」を使用する手順を示します。Etcherは以下ウェブサイトからダウンロードし、各環境にインストールしてください。

![EtcherDownload](images/balena_web.png)

[Etcherのダウンロードはこちら](https://etcher.balena.io/)


#### imgファイルの選択

ダウンロード、インストールしたEtcherを起動します。
![EtcherWrite](images/etcher02.png)

「Flash From File」より、先ほどダウンロードしたimgファイルを選択します。


#### ターゲットメディアの選択
![EtcherWrite](images/etcher03.png)

![EtcherWrite](images/etcher04.png)

「Select Target」より、先ほどダウンロードしたimgファイルを選択します。


#### イメージの展開
![EtcherWrite](images/etcher05.png)

「Flash」ボタンを押すと、イメージの展開が開始します。

![EtcherWrite](images/etcher06.png)

展開後、チェックのためValidationのプロセスが入ります。

![EtcherWrite](images/etcher07.png)

「Flash Completed!」のメッセージが出たら完了です。アンマウントしてメディアを取り出してください。


### Kakipへのメディア装着

![EtcherWrite](images/microSD.jpg)

書き終えたSDカードをKakp裏面のmicroSDカードスロットにに挿入してください。