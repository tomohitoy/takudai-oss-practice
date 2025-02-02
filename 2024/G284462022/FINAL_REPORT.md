# 自助による資産形成サービス
## G284462022 神澤友雅

### 概要
　国民皆保健制度の課題について考える。この課題の解決には、資産形成を支援するサービスが必要と考え、家計簿などの今の資産を管理するソフトウェアを作成する。また、サブスクリプションとして、健康行動に連動したサービスを提供する。ターゲットユーザーは40歳以上の方で、約7000万人である。そのうち、サービスの利用者は35万〜70万人と予想した。また、サブスクリプションの利用者は2.8万〜5.6万人と予想した。利用料は月々500円、サブスクリプションの利用料は月々2000円とし、総売り上げは1.743億〜3.486億円と算出した。構成要素は、「React Native」「Firebase」を考えた。

### 序論
　私が選んだビジネス領域は金融業である。課題として、社会保障費が増え、国民皆保健制度が実質的に破綻していることが挙げられる。これにより、個人の負担が増えたり、医療サービスの質を下げることでコストを削減することが予想される。
　解決策として私は、よりよい医療サービスを受けるために資産形成を実現し、また、運用を支援するサービスが必要だと考えた。特に、認知機能低下者向けのツールを開発することで、より多くの人が資産形成を実現できる。そこで、そのためのサービスについて私の考えをこのレポートで述べる。

### 本論
　はじめに、サービスについて述べる。サービスの内容としては、家計簿などの今の資産を管理するソフトウェアを提供することを考えた。特に、認知能力が低下している人や機械を使い慣れていない高齢者向けの簡単なツールを意識したGUIで作成し、管理だけでなく生活の中で節約出来る部分を算出して利用者に活用してもらうことを考えている。また、利用者を増やすためにサブスクリプションとして、月額2000円をいただき、健康行動に連動したサービスを提供する。具体的には健康行動の内容と利用日数によって、何かあった際の医療費の5%〜15%をこちらで負担するというものである。

　次にターゲットユーザーと想定される利用者数を考える。ターゲットユーザーは40歳以上の方で、2023年時点では約7000万人である。その中で、実際にサービスを開始した際に想定できる利用者数を考える。既存の家計簿管理サービスとして「マネーフォワード」の利用者数を参考にすると、普及率が約15%で1500万人である。今回のサービスで、「マネーフォワード」と差別化を図ったとしても、良くて0.5〜1.0%(35万〜70万人)と私は予想した。また、サブスクリプションを利用する割合については、40歳以上の方で週一回以上受療した人数は2021年で約550万人なので、7000万人のうち約8%である。そのため、サービスの利用者にもよるが大体2.8万〜5.6万人と予想できる。これは、サブスクリプションを利用する方の目的は医療費を安くしたいからだと考えられるため、定期的に受療を受けている方の人口を計算した。

　また、想定される利用者数から売上を考える。「マネーフォワード」は月々500円なので、同じ価格で考えてみると、
500 × (35万〜70万人) = 1.75億〜3.5億円
となる。次にサブスクリプションによる売上を考える。生活習慣病を患っている方の月々の費用を15000円と仮定した時、サービスで最大2250円をこちらが負担することになる。サブスクリプションの料金は2000円としているので利用者は250円お得になる。すべての方が生活習慣というわけではなく、慢性疾患や逆に何か大きな怪我や病気に備えて利用する方もいると考えられる。このサービスは健康行動に連動してこちらの負担する金額が変動する仕組みであり、慢性疾患は利用しづらいと考えられるため、9割を15%の割引を受けられる生活習慣病を患っている方、1割を病気に備えて利用する方と仮定する。
このサービスの利用者が35万人とするとサブスクリプションの利用者は2.8万人
2.8万人 × 2000円　- 2.8万人 × 0.9 × 2250円 = -70万円
総売り上げ
1.75億 - 70万 = 1.743億 
このソフトウェアの利用者が70万人とするとサブスクリプションの利用者は5.6万人
5.6万人 × 2000円　- 5.6万人 × 0.9 × 2250円 = -140万円
総売り上げ
3.5億 - 140万 = 3.486億 
よって月々の総売り上げが1.743億〜3.486億円と計算できる。

　ソフトウェアの構成要素は、フレームワークとして「React Native」を使う。高いパフォーマンスを必要とはしておらず、よりコストが低く開発をスムーズに行えるものを考えていて、「React Native」はJavaScriptを使用しており、私はJavaScriptを勉強していたため扱いやすいと考えた。バックエンドサーバーとして「Firebase」を使う。ツールが統一されており、シンプルで使いやすいためである。また、ライセンスについては、「React Native」はMITライセンス、「Firebase」はGoogleが提供する商用サービスであり、オープンソースではない。そのため、利用する際はFirebaseの利用規約およびGoogleCloudのポリシーを確認する。

### 結論
　このサービスにより、医療サービスを受けるための資産形成をしやすくできると考えた。また、それが今の国民皆保健制度の課題の解決に近づくとも考えた。ただ、サブスクリプションのあり方はまだ未確定な部分が多いため、リリースのためにはもう少し内容を固めなければいけない。
　売り上げはサブスクリプションにより少し下がっている。これは、サブスクリプションを設ける目的が、売り上げよりも利用者を増やすことを考えたためである。それに総売り上げを見ると、十分な売上を上げれているため、小規模のサービスとして特に問題はないと私は考える。

### 参考文献

○40歳以上の人口
https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200241&bunya_l=02&tstat=000001039591&cycle=7&year=20230&month=0&tclass1=000001039601&stat_infid=000040079247&result_back=1&tclass2val=0

○既存の家計簿管理サービス「マネーフォワード」の普及率
https://corp.moneyforward.com/news/release/service/20231110-mf-press-1/#:~:text=%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E3%83%9E%E3%83%8D%E3%83%BC%E3%83%95%E3%82%A9%E3%83%AF%E3%83%BC%E3%83%89%E3%81%AF,%E6%B1%BA%E7%AE%97%E7%99%BA%E8%A1%A8%E3%81%AB%E3%81%A6%E5%85%AC%E8%A1%A8%E3%80%82

○外来で受療した人数について
https://www.mhlw.go.jp/toukei/saikin/hw/kanja/20/dl/kanjya-01.pdf?utm_source=chatgpt.com


