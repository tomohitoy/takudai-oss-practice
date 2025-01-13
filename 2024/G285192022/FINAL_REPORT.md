# 若者向け，スマホと車の連動サービス  
<br>

### G285192022  
### 柳澤朋哉  
<br>

## 1.概要  
近年,若者の自動車離れと言われている。私はその理由は，不景気なども考えられるが，若者が移動手段に困っていないのではないかと考えた。  
そこで，急速に発達するスマホの技術を自動車の技術に連携させるサービスを作成し，自動車に移動手段以外の魅力を付与することで若者の自動車保有を促したい。加えて，近年減少傾向にある若者の運転免許書の保有率上昇を目指す。  
以下が目標である。
  - スマホで気軽にカスタマイズや支援を行うシステムで，若者など自動車に関心の薄い層に業界参入を促す。  
   - 洋服や装飾品の様に自動車の外装を自由にカスタムして個性を強調できる様にするなど。  
  - スマホと車を連動させることで，車の機能でインターネット通信を利用可能にする。 
   - 自動車を防音室の様に使い，直接動画配信サイトで配信できるなど。   
<br>

## 2.ターゲットユーザ  
今回，若者の自動車保有率上昇やその後のサービスを目的としているため，ターゲットユーザは若者としている。  
したがって，若者以外のユーザは今回考えないこととするが，ターゲットユーザの範囲拡大などを今後の課題としたい。  
若者の定義と算出は以下の様に行なっている。
<br>  

- 若者:18~29歳までの者または20代の者  
  若者の人口はe-Statの2024年12月の人口推計(1)より，  
 - 20歳～24歳　626万人  
 - 25歳～29歳　651万人  
  よって合計1277万人がターゲットユーザである。  
  このサービスでは，以下の前者をメインに後者を新規で考える。  
<br>

- 自動車を保有している若者  
　インテージのデータ(2)では，20代の自動車保有率は45.6%となっている。  
　したがって，1277万人の45.6%が自動車を保有している若者。  
　よって，582.312万人。  
　今回は約582万人がメインのターゲットユーザとする。  
<br>

- 自動車を保有していない若者  
　自動車を保有していない若者は55.4%と考えられる。  
　したがって，1277万人の55.4%が自動車を保有していない若者。  
　よって，707.458万人。  
　今回は約707万人が新規参入狙いのターゲットユーザとする。  
<br>

## 3.ビジネスモデル  

 - ビジネスモデルはスマホを連携させるため，アプリを用いてサブスクリプション型サービスを採用する。  
<br>

### 機能  
- ユーザ情報と車の情報を紐付けて，スマホから車のカスタムや車体の色などを変更申込できる。  
- 保険や車検情報をスマホで確認，変更，更新ができる。  
- SNSやYoutubeなどの動画配信サービスを車内の画面などで確認，操作できる。  
- スマホをドライブレコーダーや音楽プレイヤーや高速道路の支払い(ETC的な)として使える。  
- 契約後も新機能の開発，実装を続けていく。  
<br>

### 年間売上推定  
 - 多くのサブスクリプションサービスの料金は各サービス月額1000円前後が多いため，一般的なサブスクサービスの運営，サーバ運用，保守には
 　そのぐらいの費用がかかると仮定する。
 　したがって，今回は基本使用料を月額1000円として計算する。  
   <br>
 　年間売上高 = 1000円　* 利用人数　* 12(月)　となる。  
   <br>
   さらに，今回は参考のサイト(3)を参考に市場占有率を考え，車保有者は競合が少ないことより安定トップシェアを目標にする。  
   安定トップシェアは全体の41.7%より，利用者は約243万人で計算する。  
   <br>
   車未保有者は，参入障壁があるため全体の市場認知シェアとされる10.9%を目標にする。  
   よって，利用者は約77万人で計算する。  
   <br>
   上記の内容より，目標利用人数は320万人とする。  
   <br>
   よって，年間売上高 = 1000円　* 3200000人　* 12ヶ月  
   　　　　年間売上高 = 38400000000円  
   したがって，年間売上高は384億円となる。  
<br>

## 4.利用する技術
 - クラウドコンピューティング
 - アプリ開発用の言語(Swiftやjavaなど)
 - 顧客情報を保管，利用するデータベース
 - オンラインショップ構築

<br>

## 5.利用するOSSとライセンス  
OSS名(ライセンス)と記述する。 
<br>

- Apache HTTP Server(Apache License 2.0)
 - 選定理由：無料であるため，サービスの料金を変更，調節しやすくなる。

- MySQL(商用ライセンス,GPL)　　
 - 選定理由：ユーザ情報などを保管するために使用。多くのサービスに使用されているため，他サービスとの連携しやすい。及び，認知度から保守などの知識のある技術者の多さから採用。  
<br>

- WordPress(GPLv2 (またはそれ以降))  
 - 選定理由：スマホ上からカスタマイズのパーツを注文できるECサイトを構築するため。  


## 6.終わりに
今回は若者を対象とした新サービスの提案を行なった。今後，自動車業界は自動運転などによりさらに運転免許書の取得率が下がると考えられる。そこで，自動車が自動運転に切り替わる前に新たな魅力や購買意欲を沸かせることが必要である。現在，20代のスマホの普及率が9割以上とされている。新サービスや流行などがスマホで行われているため，それを自動車に連携することで，より便利になると考えた。今後も，スマホによる便利な増えていくので，今回提案したサービスも発展の余地があると考えられる。  
今回はターゲットユーザとしなかった30代以上の年代にも普及できるサービスを考えること今後の課題としたい。  
<br>

## 参考文献一覧  
(1) ["人口推計 年齢(5歳階級)、男女別人口(2024年7月確定値、2024年12月概算値)" . e-Stat](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200524&tstat=000000090001&cycle=1&year=20240&month=24101212&tclass1=000001011678&result_back=1&tclass2val=0),(参照2025-1-2)  

(2) [磯上尚規 . "インテージ「知るギャラリー」2024年7月9日公開記事"](https://gallery.intage.co.jp/car-purchase2024/),(参照2025-1-2)  

(3) [山崎雄司 . "マーケットシェアとは？意味や種類、計算方法、メリット、クープマン目標値" . Digital Marketing Forum](https://www.customer-rings.com/dmf/article/wzv42xa_7af),(参照2025-1-2)  

(4) ["Apache License 2.0" . Apache Software Foundation](https://www.apache.org/licenses/LICENSE-2.0),(参照2025-1-2)  

(5) ["OEM、ISV、VAR 向け MySQL 商用ライセンス" . MySQL](https://www.mysql.com/jp/about/legal/licensing/oem/),(参照2025-1-2)  

(6) ["GNU パブリックライセンス" . WordPress Foundation](https://ja.wordpress.org/about/license/),(参照2025-1-2) 