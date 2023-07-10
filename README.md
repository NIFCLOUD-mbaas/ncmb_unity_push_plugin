# NIFCLOUD Mobile Backend Push Notification Plugin for Unity


こちらはニフクラmobile backendのUnityプッシュ通知用プラグインになります。

こちらは [ニフクラmobile backend Unity SDK](https://github.com/NIFCLOUD-mbaas/ncmb_unity) と組み合わせて利用する必要があり、単体では動きませんのでご注意ください。
詳細の利用方法については [ドキュメント](https://mbaas.nifcloud.com/doc/current/push/basic_usage_unity.html) をご確認し、ご利用ください。

---
## 動作環境

- Unity 2021.x
- Android 8.x〜13.x, API level 26.0〜33.0
- iOS 13.x〜16.x
(※2023年07月時点)

## 依存ライブラリ

プッシュ通知機能を利用する場合は、以下のライブラリが必要です。
(package内部に含まれているので、別途用意する必要はありません。)

- Android Support Library
- Google Play Service SDK
- Firebase Service Library


### テクニカルサポート窓口対応バージョン

テクニカルサポート窓口では、1年半以内にリリースされたSDKに対してのみサポート対応させていただきます。
定期的なバージョンのアップデートにご協力ください。  
※なお、mobile backend にて大規模な改修が行われた際は、1年半以内のSDKであっても対応出来ない場合がございます。  
その際は[informationブログ](https://mbaas.nifcloud.com/info/)にてお知らせいたします。予めご了承ください。  

- v1.0.0 ～ (※2023年7月時点)

[開発ガイドライン](https://mbaas.nifcloud.com/doc/current/common/dev_guide.html#SDK%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)をご覧ください。


## 初期設定

* 必ず事前にncmb_unityをインポートしてください。また、ncmb_unityの初期化については[プッシュ通知ドキュメント](https://mbaas.nifcloud.com/doc/current/introduction/quickstart_unity.html)をご確認し、行なってください。
* 詳細については[プッシュ通知ドキュメント](https://mbaas.nifcloud.com/doc/current/push/basic_usage_unity.html)を併せてご確認ください.

## ライセンス

LICENSEファイルをご覧ください。

## その他

- 内部では以下のプロジェクトをビルドしたライブラリを利用します
   - [NIFCLOUD Mobile Backend Push Notification Android Plugin Project](https://github.com/NIFCLOUD-mbaas/NcmbFcmPlugin)
