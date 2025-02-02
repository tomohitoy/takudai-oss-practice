# タイトル
## G284432022 河上大志
### はじめに
　私の興味を持っているビジネス領域・業界はバーチャルリアリテ
ィ（VR）業界である。この業界において注目する課題は、VR体験を
提供するためのコンテンツ制作に多くの時間やコストがかかるとい
う点である。そこで、一度作成されたVRコンテンツを他のユーザー
と共有することで、制作負担を軽減するWebサービスを提供する。
## 1.課題と解決策
　VRコンテンツ制作には、プログラミングや3Dモデリングなどの専
門知識が必要であり、これが普及の妨げとなっている。また、個人
ユーザーや中小事業者は大手企業のようなリソースを持たないた
め、コンテンツ制作に大きな課題を抱えている。
この課題を解決するために、制作済みのVRコンテンツを共有し、テ
ンプレートとして再利用できる仕組みを提供する。ユーザーは既存
のコンテンツを編集して独自の体験を作り上げることが可能とな
る。
## 2.ターゲットユーザー
このサービスの主な対象は、VR体験を提供または利用したい個人お
よび事業者である。
### 2-1.計算法
以下は、VRデバイスの普及状況に基づく潜在的なユーザー数の試算
である。

:前提情報
日本国内のインターネット利用者数：約1.125億人
メタバースの認知度：83%
メタバースの利用率：5.5%
souken[https://metaversesouken.
com/metaverse/diffusion-rate/]のデータから引用


日本国内のインターネット利用者のうち、メタバースという言葉を
知っている人は
1.125億人 × 0.83 = 約9,337万人

さらに、実際にメタバースを利用したことのある人の割合を基に潜
在ユーザー数を算出します。仮にこのサービスが既存の利用者層を
対象とする場合
9,337万人 × 0.055 = 約513万人

初期段階の導入目標として、利用者の1%がこのサービスを使用する
と仮定すると

513万人 × 0.01 = 約5万1,300人
## 3.ビジネスモデル
月額制：ユーザーの月額料金から利益を得る
### 3-1.推定年間売上高
:前提情報
教育事業者: 約36万人 引用:souken :https://
metaversesouken.com/metaverse/diffusion-rate/
ユーザー数: 約5万1,300人(利用者はメタバースユーザー全体の1%想定)

サービス利用者が月額料金を支払うと仮定
月額料金：仮に1,000円と設定（適宜調整可能）
計算方法
月額売上 = 月額料金 × ユーザー数
月額売上 = 5万1,300人 × 1,000円
月額制での推定売上は、約5,130万円



## 4.技術構成要素
### 4-1.選定した技術
選定技術|選定理由
Unity(https://unity.com/ja)|メタバース空間の構築に適しており、拡張性が高い。
WordPress(https://wordpress.com/ja/)|サービスの基本サイト構築と教育資料共有機能に利
用。
### 4-2.使用するOSSとライセンス
使用するOSS名|ライセンス|使用する理由
A-Frame(https://aframe.io/)|MITライセンス|ウェブブラウザでVR体験を提供する
OSS。学習コストが低い。
### 終わりに
本サービスはメタバースの「認知度の高さ」と「利用率の低さ」
に着目した。ユーザー同士が共有できるサービスにする事で普及率向上に繋げていきたい

引用:souken https://metaversesouken.
com/metaverse/diffusion-rate/
souken  https://metaversesouken.com/metaverse/diffusion-rate/
Unity https://unity.com/ja
WordPress https://wordpress.com/ja/
A-Frame https://aframe.io/