## 自動販売機（オブジェクト、DOM、イベント処理）のミニレポート
### Q4-1. Itemクラスのメソッドについて説明せよ。
* showItemListがクラスメソッドである理由を考察せよ。
* 商品一覧をクラス全体で参照することができるようにするため
* buyItemがインスタンスメソッドである理由を考察せよ。
* 商品の在庫をbuyItemでのみ変更できるようにするため
### Q4-2. 商品の購入ボタンをクリックすると、どのような処理でセルの値が減少するか説明せよ。
* 購入された商品の在庫数のセルをどのようにして特定するのか説明せよ。
* 在庫数をidで確認しgetElementByIdで特定を行っている
* 特定したセルの値をどのように変更するのか説明せよ。
* buyItemで特定したセルの値をstock--で変更している
### Q4-3. 感想
* 今回の課題で苦労したこと
* 配列の内容を項目ごとに出力させる際にfor文を使うということがわからずつまずいた
* 演習を通して理解できたこと
* 配列の内容を表示させる際の手法を教材などで調べることによって理解することができた
* この自動販売機プログラムの追加機能や課題など
追加機能として、商品を何個か購入したら在庫が追加されるなどのプログラムを入れることでより面白いプログラムになるのではないかと感じた
