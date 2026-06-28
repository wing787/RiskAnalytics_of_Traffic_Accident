# RiskAnalytics_of_Traffic_Accident
## Outline
wip
## Usage Data
### Road Data
- 道路データ ー 国土数値情報: [リンク](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N13-2024.html)
    - 2026/06/28時点
    - ファイルフォーマット: GML, Shape, GeoJSON
    - 配信単位: 3次メッシュ単位
    - 座標系: JGD2011(EPSG: 6668)
### Trafic Accident Statistics
- 交通事故統計情報のオープンデータ ー 警察庁: [リンク](https://www.npa.go.jp/publications/statistics/koutsuu/opendata/index_opendata.html)
    - 2026/06/28時点
    - ファイルフォーマット: CSV
    - 配信単位: 年度別
    - 座標系: 特に記載なし、緯度経度なのでWGS84(EPSG: 4326)と解釈