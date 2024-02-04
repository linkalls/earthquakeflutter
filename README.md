# 地震情報アプリ

このアプリは、日本の地震情報を取得し、表示するためのものです。現在、Amazon App Storeでアプリが公開されています。

## 機能

- 地震情報の取得と表示
- 地震情報の更新（プルダウンで更新）
- 地震情報のソート（新しい情報が上に来るように）

## 使用技術

- Dart
- Flutter
- http パッケージ（APIからデータを取得するため）
- intl パッケージ（日付の解析とフォーマットのため）

## 使い方

1. アプリを起動します。
2. 地震情報が自動的に取得され、リストとして表示されます。
3. 最新の情報を取得するには、リストをプルダウンして更新します。

## Amazon App Store での公開

アプリはAmazon App Storeでも公開されています。詳細は以下のリンクからご確認いただけます。
[Amazon App Store - 地震情報アプリ](https://www.amazon.co.jp/gp/product/B0CTY69K1M)

## 注意事項

このアプリはデモ用であり、地震情報の正確性や完全性を保証するものではありません。地震情報は公式の気象庁の発表をご確認ください。

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細はLICENSEをご覧ください。

## Todoリスト

- ネットがないときに前回表示したデータを保持して、ネットに接続したら自動的に更新する処理

