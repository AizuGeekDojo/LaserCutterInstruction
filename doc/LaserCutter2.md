# 加工のしかた

## 目次
1. 事前知識
1. 使用時の手順
1. 使用後の手順
1. 覚えておくといいこと
1. 終わりに

## 事前知識

### レーザーカッタの種類
Aizu Geek Dojo には２種類のレーザーカッタが１台ずつあります．性能が異なりますが，基本的な使い方は同じです．
| Speedy 100 | Speedy 300 |
| :--------: | :--------: |
| <img src="image/speedy100.jpg" width=500vw> | <img src="image/speedy300.jpg" width=500vw> |

### 各部の名称
- レーザ出力部
    | Speedy 100 | Speedy 300 |
    | :--------: | :--------: |
    | <img src="image/laser-output-speedy100.jpg" height=400vw> | <img src="image/laser-output-speedy300.jpg" height=400vw> |
- 操作パネル\
    <img src="image/button.jpg" height=400vw>
- ハニカムボード
    | Speedy 100 | Speedy 300 |
    | :--------: | :--------: |
    | <img src="image/honeycomb-board-speedy100.jpg" height=400vw> | <img src="image/honeycomb-board-speedy300.jpg" height=400vw> |

## 使用時の手順
> [!NOTE]
> この資料では，カットするデータは準備してあるものと仮定します．
1. データを Aizu Geek Dojo のデスクトップ PC に何らかの方法で移動する
1. Aizu Geek Dojo のデスクトップ PC で Ruby を開く\
    <img src="image/open-ruby.png" height=400vw>
1. デスクトップ PC 本体に貼ってある メールアドレスとパスワードを用いてログインする\
    <img src="image/ruby-login.png" height=400vw>
1. Import file ボタンを押してデータをインポートする\
    <img src="image/ruby-import.png" height=400vw>
1. インポートしたファイルの行をクリックする\
    <img src="image/ruby-after-import.png" height=400vw>
1. カットする線を選択して赤色にする\
    <img src="image/ruby-design.png" height=400vw>\
    <img src="image/ruby-design-modified.png" height=400vw>
1. 彫刻する領域を選択して黒色にする
1. CREATE JOB ボタンを押す\
    <img src="image/ruby-create-job.png" height=400vw>
1. カットする材料を選択する\
    材料名（アクリル・MDF）と厚さをカットする材料と合わせれば大丈夫です．（アクリル: acrylic）\
    <img src="image/ruby-material.png" height=400vw>\
    <img src="image/ruby-material-select.png" height=400vw>
1. 集塵脱臭装置にカットしたい材料用のフィルタが入っていることを確認する\
    画像に示すフィルタ表示がカットしたい材料のほうになっていれば大丈夫です．もしそうなっていなければ，別途資料（WIP）を参考に集塵脱臭装置のフィルタを交換してください．\
    <img src="image/filter-indicator.jpg" height=400vw>
1. レーザーカッタの蓋が閉まっていること確認し、左奥にある電源をつける
1. 初期化（ピーと音がなる）まで待つ
1. 蓋を開ける
1. カットしたい材料を設置する
1. レーザ出力部を操作パネルの位置調整十字キーを用いて加工する箇所の中央付近に移動する
1. レーザ出力部に焦点合わせ金具をひっかける\
    金具はレーザーカッタの左奥の 3D プリンタ製の入れ物の中に入っています．また，Speedy100 と Speedy300 で金具は別物なので気を付けてください．
    | Speedy 100 | Speedy 300 |
    | :--------: | :--------: |
    | <img src="image/kanagu-speedy100.jpg" height=400vw> | <img src="image/kanagu-speedy300.jpg" height=400vw> |
    | 三日月型になっているところにひっかける | 溝になっているところにひっかける |
1. ハニカムボードの高さを操作パネルの高さ調整キーを用いて焦点合わせ金具が倒れるギリギリまで上げる
1. レーザ出力部を操作パネルの位置調整十字キーを用いて切断開始場所に移動する
1. 蓋を閉じる
1. 印刷する位置を決める\
    <img src="image/ruby-determine-position.png" height=400vw>
1. PUSH TO LASER ボタンを押す\
    <img src="image/ruby-push-to-laser.png" height=400vw>
1. 加工スタートボタンを押す\
    <img src="image/ruby-start-laser.png" height=400vw>

## 使用後の手順
1. 加工したものを取り出す
1. 蓋を閉める
1. レーザ出力部を左上付近に移動する
1. 操作パネルの高さ調整キーを用いてハニカムボードを一番下まで下げる
1. 左奥の電源を切る
1. ハニカムボードを外してレーザーカッタ内に落ちている破片を掃除する\
    | Speedy 100 | Speedy 300 |
    | :--------: | :--------: |
    | <img src="image/cleaning-speedy100.jpg" height=400vw> | <img src="image/cleaning-speedy300.jpg" height=400vw> |
1. ハニカムボードをもとの位置に戻す\
    ハニカムボードの裏を見たらわかりますが，ハニカムボードの土台とはまるようになっています．

## 覚えておくといいこと
デザイン画面で Fit to design のボタンを押すと余分な余白がなくなり，準備画面で位置調整がしやすくなります．\
<img src="image/ruby-fit-to-design.png" height=400vw>

準備画面でデザインの位置決めをする際，レーザ出力部の位置は Ruby とレーザーカッタで同期されています．レーザ出力部の位置を操作パネルを用いて動かすと Ruby にもそれが反映されます．Ruby では，レーザ出力部の位置にデザインの位置を合わせることができるため，レーザ出力部の位置を操作パネルから調整して，Ruby でデザインの角をレーザ出力部の位置に合わせることで比較的楽に位置調整ができます．

レーザ出力部の位置は Ruby とレーザーカッタで同期されているため，レーザ出力部の位置を Ruby でドラッグアンドドロップすると，レーザーカッタでもそれが反映されます．これを利用して，デザインが置いた材料の大きさからはみ出していないかを確認することができます．

材料の選択を間違えて彫刻が薄すぎた場合，準備画面でカットのチェックマークを外してもう一度加工を始めると，彫刻のみを繰り返すことができます．材料の選択を間違えてカットで切りきれなかった場合も同様に，準備画面で彫刻のチェックマークを外してもう一度加工を始めると，カットのみを繰り返すことができます．ただし，材料を一度持ち上げたりして確認した場合は，とても気を付けて元の位置に戻さないときれいに繰り返すことはできません．\
<img src="image/ruby-repeat.png" height=400vw>

操作パネルの上部にある３つのボタンには、それぞれ集塵脱臭装置オンオフ、スリープモードのオンオフ、一時停止が割り当てられています。集塵脱臭装置は加工が始まるとオンになり、その後しばらくすると自動でオフになるため，使う機会は少ないと思います．何分か電源をつけたままレーザーカッタを放置していると，自動でスリープモードになります．スリープ中はレーザ出力部の移動やプラットフォームの高さ調整などはできないのでボタンでスリープモードを解除する必要があります．一時停止は，加工中に一度加工を止めたい場合に用います．

## Trotec 公式ドキュメント
- [マニュアル](https://www.troteclaser.com/ja/helpcenter/downloads/manuals)
- [動画チュートリアル](https://www.troteclaser.com/ja/helpcenter/software/ruby/video-tutorials)
- [Rubyで画像のレーザー加工](https://www.troteclaser.com/ja/helpcenter/software/ruby/dealing-with-images-in-ruby)
- [ビットマップトレーシング](https://www.troteclaser.com/ja/helpcenter/software/ruby/bitmap-tracing)
- [材料パラメータの設定と管理](https://www.troteclaser.com/ja/helpcenter/software/ruby/setting-up-and-managing-material-parameters)
- [動的データの処理](https://www.troteclaser.com/ja/helpcenter/software/ruby/handling-dynamic-data)
- [ベクター加工](https://www.troteclaser.com/ja/helpcenter/software/ruby/vector-processing)