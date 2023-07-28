# Jalan_Scraping

じゃらんの特定のカテゴリに属する観光地の全てのレビューを取得するプログラムです.

カテゴリのURLを適時変更してください.

GoogleDriveに各カテゴリ/各観光地のレビューがjsonファイルで保存されます.

<spt_ID>_<観光地名>.json {

  "name" : 観光地名,
  
  "spt_ID" : 観光地ID,
  
  "adress" : 観光地の住所,
  
  "reviews" : [{
  
    "title" : レビューのタイトル,
    
    "review" : レビュー本文,
    
    "posetd_data" : レビューが投稿された日,
    
    "star" : レビューの星の数,
    
    "tag" : レビューのタグ,
    
    "auther" : レビュー著者の 年代／性別
    
  }]
  
}
