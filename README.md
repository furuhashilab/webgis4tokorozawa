# webgis4tokorozawa
所沢市GIS講習会用公開リポジトリ

## 0. 講義資料
 * [スライド(PDF)](https://speakerdeck.com/fullfull/20230815-suo-ze-shi-gisyan-xiu-hui-pei-bu-zi-liao)

## 1. 実習用データ

### 1.1. 住所から緯度経度への簡単変換
#### 1.1.1. [所沢市 小児急患診療医師派遣協力医療機関データ](https://www.city.tokorozawa.saitama.jp/iryo/kyukyugairainogoannai/syounikyuukansinryou.html)
 * [小児急患診療医師派遣協力医療機関(CSVファイル)](https://github.com/furuhashilab/webgis4tokorozawa/blob/main/data/%E5%B0%8F%E5%85%90%E6%80%A5%E6%82%A3%E8%A8%BA%E7%99%82%E5%8C%BB%E5%B8%AB%E6%B4%BE%E9%81%A3%E5%8D%94%E5%8A%9B%E5%8C%BB%E7%99%82%E6%A9%9F%E9%96%A2.csv)

 * [小児急患診療医師派遣協力医療機関(GeoJSONファイル)](https://github.com/furuhashilab/webgis4tokorozawa/blob/main/data/%E5%B0%8F%E5%85%90%E6%80%A5%E6%82%A3%E8%A8%BA%E7%99%82%E5%8C%BB%E5%B8%AB%E6%B4%BE%E9%81%A3%E5%8D%94%E5%8A%9B%E5%8C%BB%E7%99%82%E6%A9%9F%E9%96%A2.geojson)

 * [小児急患診療医師派遣協力医療機関(Excelファイル)](https://github.com/furuhashilab/webgis4tokorozawa/blob/main/data/%E5%B0%8F%E5%85%90%E6%80%A5%E6%82%A3%E8%A8%BA%E7%99%82%E5%8C%BB%E5%B8%AB%E6%B4%BE%E9%81%A3%E5%8D%94%E5%8A%9B%E5%8C%BB%E7%99%82%E6%A9%9F%E9%96%A2.geojson)

 * [小児急患診療医師派遣協力医療機関(Googleスプレッドシート)](https://docs.google.com/spreadsheets/d/1eVRpkVNpLuscOGn2nxXMwvPQVOPpe7jZJYcKKOTi-cY/edit?usp=sharing)


#### 1.1.2. 関連サイト
 * [地理院地図](https://maps.gsi.go.jp/)
 * [Jageocoder](https://jageocoder.info-proto.com/)
 * [Googleマイマップ](https://www.google.com/maps/d/u/0/) : あくまで参考情報として

---

### 1.2. Shape(シェープ)を捨て、GeoJSON(ジオジェイソン)へ
#### 1.2.1. [所沢市オープンデータ on 埼玉県オープンデータポータル](https://opendata.pref.saitama.lg.jp/data/organization/1828149d-1a58-4c42-90a9-18780d07ccb6?tags=%E4%BD%8F%E6%B0%91%E5%90%91%E3%81%91%E6%83%85%E5%A0%B1+%E6%9A%AE%E3%82%89%E3%81%97%E3%81%AE%E6%83%85%E5%A0%B1) 
 * [とことこマップ「福祉関連」(Shapeファイル)](https://opendata.pref.saitama.lg.jp/data/dataset/c12658b6-c75e-4c55-90d4-fb7a44776880/resource/34df5645-a227-48d2-8649-05c9c22c62d5/download/tokotokomapfukusikannren.zip)
 * [【所沢市】避難所マップ(Shapeファイル)](https://opendata.pref.saitama.lg.jp/data/dataset/eaec08b2-e2a2-4812-b7c1-b9f1ae3128e9/resource/9415b6f4-8017-4192-b5b1-8d0d92a87b29/download/hinanjyo20190320.zip)

#### 1.2.2. 関連サイト
 * [OGRE](http://ogre.adc4gis.com/)
 * [GeoJSON.io](https://geojson.io/)
 * [ChatGPT Code Interpreter](https://chat.openai.com/?model=gpt-4-code-interpreter)

---

### 1.3. 地理院地図を使いこなそう
 * [地理院地図](https://maps.gsi.go.jp/)
 * [地理院地図Vector](https://maps.gsi.go.jp/vector/)
 * [地理院地図ソースコード on GitHub](https://github.com/gsi-cyberjapan/gsimaps)


## 2. おまけ
 * 質問などがあったら[古橋のTwitter(X)アカウント](https://twitter.com/mapconcierge) へお気軽に！
