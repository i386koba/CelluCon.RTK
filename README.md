# CelluCon.RTK
## ネットワーク型RTK測量による数センチメートル誤差のGPS軌跡
* ネットワーク型RTK測量とは、利用者が現場で取得した衛星データと、周辺の電子基準点の観測 データから作成された補正情報を組み合わせ、リアルタイムでcm級の測量を効率的に行う方式です （RTK：リアルタイム・キネマティック）。
* ネットワーク型RTK測量計算は rtklib http://www.rtklib.com/ が有名ですので利用していきたいです。
* GPSモジュール（u-blox8）でRTKできるとのこと2017.6に [GM-8013T]] http://www.aitendo.com/product/11460 買ってありますが、まだいじくれてないです。 
* ついでに u-blox GPSモジュール [NEO6M5PSMA-U]　http://www.aitendo.com/product/15499 もRTK出来るじゃないかと購入してあります。
* ラジコンに搭載したu-blox GPSデータをWebRTCで送信し、Web画面のPCにも u-blox GPSを取り付けて、PCでrtklibで計算すればよいのかと思います。

