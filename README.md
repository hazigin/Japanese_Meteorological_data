# Japanese_Meteorological_data



1872年1月1日～2021年8月8日まで1時間毎の全国の気象データを以下の気象庁のサイトよりスクレイピングしました。

過去の気象データ・ダウンロード
https://www.data.jma.go.jp/gmd/risk/obsdl/

各カラムは以下の通りです。

年月日時,  
気温(℃),気温(℃)_品質情報,気温(℃)_均質番号,  
降水量(mm),降水量(mm)_品質情報,降水量(mm)_均質番号,  
日照時間(時間),日照時間(時間)_品質情報,日照時間(時間)_均質番号,  
日射量(MJ/㎡),日射量(MJ/㎡)_品質情報,日射量(MJ/㎡)_均質番号,  
積雪(cm),積雪(cm)_品質情報,積雪(cm)_均質番号,  
降雪(cm),降雪(cm)_品質情報,降雪(cm)_均質番号,  
風速(m/s)1,風速(m/s)1_品質情報,風向,  
風速(m/s)2_品質情報,風速(m/s)2_均質番号,  
蒸気圧(hPa),蒸気圧(hPa)_品質情報,蒸気圧(hPa)_均質番号,  
相対湿度(％),相対湿度(％)_品質情報,相対湿度(％)_均質番号,  
海面気圧(hPa),海面気圧(hPa)_品質情報,海面気圧(hPa)_均質番号,  
現地気圧(hPa),現地気圧(hPa)_品質情報,現地気圧(hPa)_均質番号,  
雲量(10分比),雲量(10分比)_品質情報,雲量(10分比)_均質番号,  
露点温度(℃),露点温度(℃)_品質情報,露点温度(℃)_均質番号,  
天気,天気_品質情報,天気_均質番号,  
視程(km),視程(km)_品質情報,視程(km)_均質番号  

※カラムの構成はstationNumの先頭がaの地点とsの地点で一部違いがあります。

それぞれの観測値に品質情報と均質番号がついています。  
詳細はダウンロード元である気象庁のサイトでご確認下さい。


観測地点の一覧は　[観測地点一覧.xlsx](https://github.com/hazigin/Japanese_Meteorological_data/blob/main/%E8%A6%B3%E6%B8%AC%E5%9C%B0%E7%82%B9%E4%B8%80%E8%A6%A7.xlsx)　に記載しています。 各観測地点について一つのcsvにまとめて、zipで圧縮しています。展開するとそれぞれ130～140M位です。

[2022/02/21]
全1662カ所の収集を完了しました。2022/8/9より2021年8月9～2022年8月8日までの期間のデータの収集/追加を再開する予定です。

[2022/01/21]
都道府県毎にフォルダを分けました。
 
[2021/11/06]
各観測地点の緯度/経度情報から住所と郵便番号を調べ追加しました。

[免責]  
当データの利用によって生じた障害等に関し、当方は一切責任を負うものではありませんのでご了承ください。
