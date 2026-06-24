# 宮崎県北地区同盟 ホームページ

宮崎県北地区同盟の法人団体向けホームページです。

## 構成

- `index.html`：トップページ
- `assets/css/style.css`：デザイン
- `assets/js/main.js`：メニュー、フォーム表示などの軽い動作
- `robots.txt`：検索エンジン向けの巡回抑制設定
- `.nojekyll`：GitHub Pages 用

## 公開方法

GitHub Pages を利用する場合は、GitHub のリポジトリ設定から以下を設定してください。

1. `Settings` を開く
2. `Pages` を開く
3. `Build and deployment` の Source を `Deploy from a branch` にする
4. Branch を `main`、Folder を `/root` にする
5. 保存する

## 検索エンジン対策

検索結果に表示されにくくするため、以下を設定しています。

- `index.html` に `noindex,nofollow,noarchive,noimageindex` を設定
- `googlebot` / `bingbot` 向けの指定を追加
- `robots.txt` で `Disallow: /` を設定

GitHub Pages の静的サイトでは完全な閲覧制限にはなりません。より厳密に制限したい場合は、アクセス制限を設定できる公開環境を利用してください。

## 編集が必要な箇所

初期状態では、所在地・電話番号・メールアドレスなどは仮表記です。正式情報が確定したら `index.html` の以下を差し替えてください。

- 団体概要
- 所在地
- 電話番号
- メールアドレス
- お知らせ
- 活動内容

## 注意

掲載文言はたたき台です。正式な団体規約、活動実績、問い合わせ先に合わせて調整してください。
