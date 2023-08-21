# Vital-Manager

Vital management application made with AppSheet.

## About
日々のバイタル（体温、脈拍、血圧、...）を登録して一覧やチャートを表示するアプリです。

本アプリはAppSheetで作っているため、当リポジトリではアプリの説明と課題の管理をしています。

## Background
不注意の怪我で入院することになって、ベッドの上でなにかできないかと考えていたところ、バイタルの管理アプリを思いついて作り始めました。

今朝8/14 4am頃に思いついて、appsheet database から作り始めて6am頃には下地ができました。

その後、バイタルの各項目をチャートにしたり、一覧の表示項目を調整したりしています。

ちなみに現状はベッドから起き上がれないので、横になったままスマホ(Android)のみで作っています。

## Install
To install 'Vital Manager' on your mobile device, click on https://www.appsheet.com/newshortcut/1912d1be-8cbb-4371-bc0f-006924c93ca8

![Installer QRコード](https://user-images.githubusercontent.com/948237/260847222-31714b8a-f2b0-4872-96b8-c0904048f424.png "Installer QRコード")

## Functions
- 患者管理（患者ID、氏名、概要、入院日）
- バイタル管理（体温、脈拍、血圧上下、血中酸素濃度）
- 排泄管理（日時、排尿有無、量、排便有無）

排泄管理は午前5時から翌午前5時までを集計単位として `排尿量 > 0` の回数を日毎に合計しています。

## Screenshots
[スクリーンショットまとめ](https://github.com/kazweda/Vital-Manager/issues/23)
## References
- 共有、公開について
[AppSheetの作品公開方法](https://note.com/mahalo_/n/nffef1aa47f82)
- ダッシュボードデザイン
[配置のコツ](https://youtu.be/ZaOwjePORKo)
