# Jalan_Scraping

じゃらんの特定のカテゴリに属する観光地の全てのレビューを取得するプログラムです.

カテゴリのURLを適時変更してください.

GoogleDriveに各カテゴリ/各観光地のレビューがjsonファイルで保存されます.

---

<カテゴリ>/<spt_ID>_<観光地名>.json

このJSONファイルは観光地の詳細情報とレビュー情報を持っています。

- **name** : 観光地名
- **spt_ID** : 観光地の一意識別子
- **address** : 観光地の物理住所
- **reviews** : 観光地についてのユーザーレビューの配列。各レビューは以下の項目を含みます。
  - **title** : レビューのタイトル
  - **review** : レビューの本文
  - **posted_date** : レビューが投稿された日付
  - **star** : レビューの星評価
  - **tag** : レビューに付けられたタグ
  - **author** : レビューを書いたユーザーの年代と性別
