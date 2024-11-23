# 道路交通センサスマップ2015 on MapLibre GL JS
## Public Website
https://shi-works.github.io/road-traffic-census-map-2015/

![image](https://github.com/shi-works/road-traffic-census-map-2015/assets/71203808/02f24eb4-8737-4d68-a9ce-52082e7c98ba)

## Data Source
### 国土交通データプラットフォームver2.1 令和4年3月30日公開
#### 平成27年度全国道路・街路交通情勢調査一般交通量調査（道路交通センサス）
- 出典（タイルURL）：https://data.mlit-data.jp/traffic_census/{z}/{x}/{y}.pbf
- ライセンス：[政府標準利用規約（第2.0版）に準拠](https://www.mlit.go.jp/link.html)

## GIS Data
- 上記のタイルURLからズームレベル11のバイナリベクトルタイル（PBF）を取得
- 取得したPBFからGeoJSON、GeoParquet、PMTilesを作成
### PMTiles形式
`https://xs489works.xsrv.jp/pmtiles-data/traffic-census/traffic_census_2015_convert.pmtiles`,205MB
### GeoParquet形式
`https://xs489works.xsrv.jp/pmtiles-data/traffic-census/traffic_census_2015_convert.parquet`,32MB

## 道路交通センサスマップ2021
https://github.com/shi-works/road-traffic-census-map-2021

## GIS Dataのライセンスについて
本データセットは[CC-BY-4.0](https://pmtiles-data.s3.ap-northeast-1.amazonaws.com/traffic-accident/LICENSE)で提供されます。使用の際には本リポジトリへのリンクを提示してください。
また、本データセットは国土交通データプラットフォームで公開されている平成27年度全国道路・街路交通情勢調査（道路交通センサス）のGISデータを加工して作成したものです。本データセットの使用・加工にあたっては、[国土交通省Webサイトのリンク・著作権・免責事項](https://www.mlit.go.jp/link.html)を必ずご確認ください。

## 免責事項
利用者が当該データを用いて行う一切の行為について何ら責任を負うものではありません。
