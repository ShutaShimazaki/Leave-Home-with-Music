# YOUR PROJECT TITLE
朝が苦手な人へ

"音楽とともに家を出る"

#### Video Demo: <URL https://www.youtube.com/watch?v=ddmLbRzls7g>

#### Description:

<!-- 最低でも複数の段落で構成され、
プロジェクトの内容、
プロジェクト用に作成した各ファイルの内容と機能、
また特定の設計を採用するか否かを議論した場合はその理由を説明する必要があります。 -->

~１プロジェクトの内容について
(WHO)
朝弱い人。目覚めてからダラダラしてしまい、
家を出るのが予定時間よりも遅くなっちゃう人。

遅刻しがちな人。休日どこかに出かけようと思っていたが、
なんだかんだお家でダラダラ過ごしてしまう人。

(WHY)
人生は 1 日 1 日の積み重ねである。
良い 1 日を過ごせるかは、いかに朝の時間を有効活用できるかにかかっている。
そして朝の時間を有効活用できるかは「いつ家を出発できるか」にかかっている。
すなわち、「スムーズに家を出発することは人生をより良いものにする」はずである。
このアプリは、ユーザーが望んだ時刻に家を出発できるためのものである。

朝早く起きることのメリットを以下に。
・毎日 1 時間早く起きるだけでも、使える時間が年間 365 時間増える計算になる。
・一日の活動時間を 8 時間と仮定すると、約 45 日分の時間が増える。
・出社前の洗濯やジョギングといった「朝活」もできるようになる
・早起きすれば体のリズムが整ううえ、
精神的なゆとりが生まれるので仕事もスムーズに始められる。
・前向きな気持ちで一日のスタートが切れる
・・朝、コーヒーを飲みながら今日のスケジュールを確認する。たった 10 分でも、この時間があることで一日を穏やかな気持ちで過ごせる
・・まどろみは「積極的な二度寝」です。二度寝はストレスを緩和する効果があると言われている。
・・率よく動ける朝に家事の 8 割を済ませておくと、ゆとりのある一日が過ごせる
・・誰にでも平等に訪れる「朝」は、外の世界も自分の心も静かな「余白」の時間です。
・・朝の時間を楽しむことは、人生を積極的に楽しむこと。
・・その小さな「朝時間」の積み重ねが、毎日をもっと素敵に彩るヒントになるでしょう。

(FUNCTION)
・起きる時間を設定できるようにして、目覚ましの要領でアラーム機能。
・家を出る時間を設定できるようにする
・カウントダウン機能(アラームが鳴った瞬間から、家を出る時間まで）

(Future - NOT realized in my final project yet..)
・起きる時間と家を出る時間という 2 つの時間を保存できるようにすることで、再設定の必要をなくす。
（大体の人は、生活サイクルが決まっているはずだから）
・カウントダウンの間、お気に入りの曲を詰め込んだプレイリストが流れ続ける。ユーザーはその曲が止まるまでに、
朝の支度を終わらせなければならないようにする。

(How to use?)

1. ユーザーは 2 つの時間をセットする。(起きる時刻, 家を出る時刻)
2. 起きる時間になるとアラームが鳴り始める。同時に、家を出る時刻までのカウントダウンがスタートする。
3. ユーザーはカウントダウンに焦りながら、カウントダウンが終わるまでに家を出る

~2.各ファイルの内容と機能
main.js: javascript で以下のことを行なった
・現在時刻の取得
・ユーザーが起床時刻と出発時刻を設定できるような機能
・ボタンを押すと設定した２つの時刻を表示する
・起床時刻になると音が流れる
・家を出るまでのカウントダウン機能

main.html:
・このアプリの肝であるカウントダウンの表示を最も大きく配置
・アラームを停止できるボタン
・時刻を選択肢形式で
・・設定した時刻を確認できる画面
・flex を使って簡易的に各要素を配置

pic1.jpeg:
html の背景
　薄い色を選んだ

アラーム音１.mp3:
　起床時刻になったら鳴る音
　よくある目覚ましの音である

~３特定の機能を実装するかの議論
・以下の機能は、時間都合上断念した。
　全て魅力的なアイデアだと思う。

・・起床時刻と出発時刻のペアを保存できる
・・そして再設定できる
/・
・アラーム音を選択肢からできる
・もしくは好きな音源をアラームにできる

・カウントダウン時に好きな音楽たちが流れて、
・音楽が終わると同時にカウントダウンが終了するような設計にする
・そのために音楽をサビだけなど、1min, 2min などきりいいところでカット
・
・カウントダウンが近づくにつれ音が大きくなる
・
・背景が user の好きな画像へ変えられる
・
・夜と朝で、（時間帯で）表示を変える
・
・〇〇デザイン：凹凸を表現するようなデザイン
・
・同世代（同性、同職種）の人の時刻設定が分かる
・
・何かパズルみたいなものを解かないと、アラーム解除できない
・寝起きタイムアタック
・数独
・
・あえて二度寝推奨
・ほんとの起床時刻より前の時刻に
・「二度寝のための時刻」を設定させる。
・
・言語を変える
・
・衝撃映像を流して目を覚まさせる

・食べる予定の朝ごはんを表示

・動画をアラーム代わりにできる

・睡眠導入の動画をアプリ上で保存できて再生可能

・天気表示

・お笑い動画など勝手に流れ出す

・何も予定がない人
・全国の、明日の平均起床時間に勝手にアラームがなる
・
・ほんとに起きた時間を記録するボタンを用意
・自分の起床時間の移り変わりを視覚化できるようにする

・起きてからやることをそれぞれタイマーで測れる。（特に家事）

(作りたいもの)
・・地震特化 sns
・・位置情報共有、目撃数、体感震度

・・Youtube で、コアなファンのためのコンテンツ
・・リトルトゥースと選択したら、他のリトルトゥースの人が見ている
　動画がおすすめで表示される

・・似た声の人の動画が再生される

・・論文の pdf に付箋をつける感じでメモ書きできる
・・論文を news 　 picks のようなコメント欄機能。
・・有識者がわかりやすく解説してくれる！！
