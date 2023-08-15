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
 * Shape → GeoJSON 変換ツール: [OGRE](http://ogre.adc4gis.com/) EPSG:3857, EPSG:4326 などのパラメータを覚える必要あり
 * GeoJSON → Shape 変換ツール: [GeoJSON.io](https://geojson.io/) 
 * Shape ←→ GeoJSON 変換可能: [ChatGPT Code Interpreter](https://chat.openai.com/?model=gpt-4-code-interpreter) ChatGPT有償契約が必要

---

### 1.3. 地理院地図を使いこなそう
 * [地理院地図](https://maps.gsi.go.jp/)
 * [地理院地図Vector](https://maps.gsi.go.jp/vector/)
 * [地理院地図ソースコード on GitHub](https://github.com/gsi-cyberjapan/gsimaps)

## 2. おまけ・質疑応答で共有したサービス
 * オフラインでナビゲーション可能な地図アプリ: [Organic Maps](https://organicmaps.app/)
 * [Yahoo!マップ](https://map.yahoo.co.jp/?lat=35.79141&lon=139.42318&zoom=12&maptype=basic )にも採用されている地図開発ツール: [Mapbox](https://www.mapbox.jp/)
 * 自転車やウォーキングの人気ルート共有: [Stravaグローバルヒートマップ](https://www.strava.com/heatmap?hl=ja-JP#12.39/139.41082/35.77513/hot/all)
 * 数千点の地点データを可視化可能なツール: [uMap](https://umap.openstreetmap.fr/ja/)
 * 地理院地図をカスタマイズして約72万地点の橋梁データなどを[ベクトルタイル化](https://github.com/gsi-cyberjapan/vector-tile-experiment)したサイト: [Q地図](https://maps.qchizu.xyz/#14/35.792893/139.461050/&base=std&ls=std%7Cmlit_road2019_bridge_01%7Cmlit_road2019_bridge_03&disp=111&lcd=mlit_road2019_bridge_03&vs=c1g1j0h0k0l0u0t0z0r0s0m0f1&d=m)
 * 市民参加型ストリートビュー: [Mapillary](https://www.mapillary.com/app/?location=Tokorozawa-Shi%2C+Japan&focus=photo&lat=35.782182390249&lng=139.44054844535&z=17&pKey=713759096881147&x=0.31533190723848137&y=0.6022423399830015&zoom=0)
 * 市民参加型ドローン空撮画像共有サイト: [OpenAerialMap](https://map.openaerialmap.org/#/139.43996787071228,35.78318032875332,16/square/133002112032122233/62a68fdc440da900061201b8?_k=nu2nvd)
 * 市民参加型バリアフリーマップ: [Wheelmap](https://wheelmap.org/) 
 * 質問などがあったら[古橋のTwitter(X)アカウント](https://twitter.com/mapconcierge) へお気軽に！
