+++
title = "T2チップ搭載MacBookAirにArchLinuxをインストールする"
description = "意外とすんなり入ります"
paginate_by = 3
date = 2022-09-17
[extra]
[taxonomies]
categories = ["blog","MacBookAir"]
tags = ["ArchLinux"]
+++

AppleT2セキュリティチップを搭載するMacBookAir9,1にArchLinuxをインストールしたので備忘録だにょ.

# Install

- [こ↑こ↓ (T2 Linux wiki)](https://wiki.t2linux.org/distributions/arch/installation/)に従って、どうぞ.
	- （T2用のカーネルであればdkmsによるモジュールの追加は必要）ないです.
	- __macOSは消さないでとっておいてください、お願いします！なんでもしますから！__(なんでもするとは言ってない）
	- ブートローダーはGRUBで、パパパっとやって終わり！

# CPUファンが回転しない

- [こ↑こ↓](https://wiki.t2linux.org/guides/fan/)にあるmbpfanが使える.自分でビルドして、どうぞ.
	- AURにあるものはたぶん使えないってそれ一番言われてるから（

# あかん、これじゃwifiが死ぬぅ！

- [https://wiki.t2linux.org/guides/wifi-bluetooth/](https://wiki.t2linux.org/guides/wifi-bluetooth/)

	- どうやらmacOSからwifiとBluetoothのファームウェアをパクってくるらしい.

# オーディオが逝キスギィ
- [https://wiki.t2linux.org/guides/audio-config/](https://wiki.t2linux.org/guides/audio-config/) 

	- configファイルがありますねぇ！

	- MacBookAir9,1だけファイルの中身が微レ違.

# 暴れるなよ...暴れるなよ...（サスペンドできない）

- 

