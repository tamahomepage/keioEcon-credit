# 慶應経済 単位チェッカー 2026

慶應義塾大学経済学部の進級条件・卒業条件を、2026年度履修案内ベースで自己確認するための単体Webアプリです。

## 公開方法

1. このフォルダをそのまま GitHub リポジトリに push する
2. GitHub の `Settings -> Pages` を開く
3. `Build and deployment` で `Source: Deploy from a branch` を選ぶ
4. `Branch: main`、`Folder: /(root)` を選んで保存する
5. 数分後に GitHub Pages のURLへアクセスする

## 構成

- `index.html`: アプリ本体
- `robots.txt`: 検索エンジン向け設定
- `sitemap.xml`: サイトマップ

## 検索エンジン向けの注意

- `robots.txt` と `sitemap.xml` は GitHub Pages の Jekyll でURLを自動解決する想定です
- `.nojekyll` は置かないでください
- 公開後は Google Search Console に登録し、`sitemap.xml` を送信すると反映が早くなります

## 免責

このアプリはβ版で、大学公式サービスではなく有志の学生が作成した自己確認用ツールです。最後はご自身で履修案内や成績表を見て判断してください。このアプリの利用によって生じたいかなる損害についても、一切責任を負いません。
