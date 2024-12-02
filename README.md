# おやま版パパママMAPについて
code for SAPPORO の[「さっぽろ保育園マップ」](https://www.codeforsapporo.org/2014/10/23/papamama/)をベースに、「おやま保育園マップ」にしました

## 使用データについて

[子育て施設一覧](https://www.city.oyama.tochigi.jp/opendata.php#)

- [子育て施設一覧_オープンデータ 211201 Preschool CSV（文字コード：UTF-8）](https://www.city.oyama.tochigi.jp/opendata_download.php?code=332)





以下は、code for SAPPOROのREADME文

```
# さっぽろパパママMAPについて

札幌市内に点在する保育所（認可、認可外）、幼稚園の位置・定員情報をマッピングした地図を作成しています。

## 利用している地図について

地理院地図で提供している地理院タイルの地図情報を利用しています。

- http://portal.cyberjapan.jp/help/development/ichiran.html

## 提供されるデータについて

札幌市で公開している保育所データ、および、国土数値情報ダウンロードサービスから入手できる福祉施設情報を元に独自のCSVデータを作成し利用しています。

- http://www.city.sapporo.jp/kodomo/kosodate/l4_01.html
- http://nlftp.mlit.go.jp/ksj/index.html

## ライセンスについて

本アプリ及びソースコードの著作権は Code for Sapporo に帰属します。  
このソフトウェアは、MITライセンスでのもとで公開されています。  
MITライセンス条件を満たす限り、自由な複製・配布・修正を無制限に行うことができます。  
ライセンス条件についてはLICENSE.txtをご覧ください。

## パパママMAPをあなたの地域で導入するには

- dataフォルダの情報を自分の地域に合わせて作成します。
- データの定義については、以下を参考にしてください。
https://github.com/codeforsapporo/papamama/blob/master/doc/dataSpecification.xls
- js/index.js の変数 init_center_coords、bing_api_key の値を変更することで、初期表示位置情報を変更できます。
```