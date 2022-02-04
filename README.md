# 2021gsc_ShioriOno
2021年度古橋ゼミ論用レポジトリ

青山学院大学 地球社会共生学部 地球社会共生学科

小野詩織 / ONO SHIORI

学生番号 1A119043

指導教員 古橋大地 教授

©︎Furuhashi Laboratory/Shiori Ono, CC BY 4.0

# 【2021年度ゼミ論】
# 高校地理必修化に向けた学習指導要領のオープンレポジトリ化
## 概要
　本研究では、高校地理必修化に向けた学習指導要領のオープンレポジトリ化に向けて、行政文書をMarkdown記法で管理する意義と管理を可能とするために克服すべき課題について取り上げる。Markdown記法で行政文書を管理する目的は以下の二点である。
* 外向けに公開する行政文書を可読性や相互編集性が高いフォーマットにし、フィードバックを得やすくしたい
* 文書作成のワークフロー上も無理が無いように、むしろ、今よりも便利にしたい
### 管理を可能とするために克服すべき課題は以下の２点であることが分かった
*　Markdown記法というデジタルワードへの恐怖心があること
*　知る→手を動かす、インプットからアウトプットにかかる時間が人それぞれであるため、大量の文章を処理しきれないこと
以上の課題を克服し、オープンな文化を通じて社会をアップデートすることを目指している。

## 始めに
　Markdown（マークダウン）とは、文書を記述するための軽量マークアップ言語のひとつである。本来はプレーンテキスト形式で手軽に書いた文書からHTMLを生成するために開発されたものだ。「書きやすくて読みやすいプレーンテキストとして記述した文書を、妥当なXHTML（もしくはHTML）文書へと変換できるフォーマット」として、ジョン・グルーバーにより作成された。簡単にまとめると、最低限のスタイリングだけは残した、書きやすくて読みやすい文章の書き方である。
 
　来年度からはじまる必修科目「地理総合」スタートに向けて、文部科学省から​​2022年度スタート予定の高等学校新学習指導要領が PDF で公開された。PDFで公開された行政文書は、編集が不可能であるため再利用しにくい。
以下は経済産業省のHPに掲載されている「GitHubを用いることの意義」だ。

[<img width="1037" alt="スクリーンショット 2021-11-14 17 14 37" src="https://user-images.githubusercontent.com/72402681/141694012-5e7f5b41-096e-45d3-bf76-3b98d5f0651f.png">](https://www.meti.go.jp/press/2021/05/20210517003/20210517003.html)


　当の行政官は行政の情報を受け取った側は次の発信者になってくれることを想像して発信手段を選びたいと主張している。そこで、共同編集可能で誰もが再利用しやすいフォーマットとして置き換えたいと感じた。文部科学省から公開された PDF を Markdown記法 に変換し、誰もが使いやすいオープンデータに整理する作業を可能な限り行いたい。

## 先行研究
1. Markdown記法の書き方
<img src="https://user-images.githubusercontent.com/72402681/141700298-f4cbbdde-5a17-4812-bf3f-1b6a1360581c.png" width="380">

<img src="https://user-images.githubusercontent.com/72402681/141785095-9ad24f00-4826-4c9b-b68c-f4027bc19f20.png" width="380">

<img src="https://user-images.githubusercontent.com/72402681/141789342-d542ab56-6a75-466d-931a-a4e4037f6dd8.png" width="380">

<img src="https://user-images.githubusercontent.com/72402681/141789357-3695ddee-b4df-47ac-93f7-50f512600737.png" width="380">

<img src="https://user-images.githubusercontent.com/72402681/141789368-c197bbb5-f046-4a88-bf4d-b90adefe032e.png" width="380">

<img src="https://user-images.githubusercontent.com/72402681/141789378-95c47634-0775-49f6-b554-1eb6f9e84ebd.png" width="380">

2. デジタル庁PM（プロジェクトマネージャー）の関治之さんのNoteを読み、作成したグラレコ↓

<img src="https://user-images.githubusercontent.com/72402681/141694685-2cd388e0-cff0-4c3a-a60e-5c556ac854b7.PNG" width="320">


## 方法
1. 行政文書をMarkdown記法で管理する意義は、先行研究で取り上げた関さんのNoteと関連する Twitterでの議論を読んで、整理する。
2. 青山学院大学の講義「社会と情報」で行った150名のMarkdown化の成果をチェックし、修正箇所を見つける。
3. 修正とマージ作業を行い、管理可能とするために克服すべき課題を分析する。
4. 「社会と情報」を受講している学生にアンケートを実施　

## 結果
### 1. Twitterでの議論から分かったこと。
Markdown記法にこだわる理由を探している人が多くいる現状。
Wordを使って文章作ってる人をターゲットにしたMarkdownエディタを作ってみたいという関さんのツイートに対して、一番いいのは見たものを見たまま編集出来て見たものをそのままMarkdownやHTMLに変換できるエディタの開発かもという声が挙げられていたことから感じた。

### 2. 青山学院大学の講義「社会と情報」で行った150名のMarkdown化の成果をチェックし、見つけた修正箇所。
１つ目。スクリーンショットができていない



２つ目。＃などの文字がそのままになっている。つまり、スペースを開けられていない。
<img src="755" alt="スクリーンショット 2022-02-05 0 36 03" src="https://user-images.githubusercontent.com/72402681/152566604-cc4cab8d-5f1c-49b6-b8dd-b68cba558749.png" width="320">

### 3. 修正とマージ作業を行い、分析した管理可能とするために克服すべき課題。
<img width="1440" alt="スクリーンショット 2022-02-05 0 26 54" src="https://user-images.githubusercontent.com/72402681/152570800-6a7713e9-8eac-44c2-a351-ea3b4496a830.png">

・古橋先生の講義を聞いて、一発で理解した学生もいれば、そうでない学生もいた。そこから、インプットからアウトプットにかかる時間が人それぞれであることが分かった。
・Markdown以前にパソコンのスキルがバラバラであることが分かった。

### 4. 「社会と情報」を受講している学生に実施したアンケートの調査結果。
<img src="668" alt="スクリーンショット 2022-02-05 1 00 47" src="https://user-images.githubusercontent.com/72402681/152568570-31f4c319-2969-49d3-9c9d-33dc78820c92.png" width="320">
<img src="667" alt="スクリーンショット 2022-02-05 0 59 33" src="https://user-images.githubusercontent.com/72402681/152568586-44339a9b-0524-4628-b2c4-f4da3fc3d5bc.png" width="320">

## 議論
「社会と情報」でMarkdown化が上手くいかなかった学生にヒアリングを実施した。すると、学生からは、Markdownって何？からのスタートだったため追い付くのに必死だったという声や、文系の私には無理かもという感情を抱いていたことが分かった。
→デジタルワードへの恐怖心が今後の課題になると痛感させられた。

## 結論
「社会と情報」で課題となった文章は50ページ程あったため、大量の文章を処理しきれなかったこともMarkdown化を面倒だと要因であると感じた。そこで、Markdown初心者への課題は、最初は2ページ分にするなど、範囲を狭めるという対策を取るべきだと考える。そして、知る→手を動かすを繰り返して慣れることが大事だと感じた。オープンな文化を通して社会をアップデートしていくためにはまず「知る」そして「手を動かす」ところから始めていく。また、デジタルワードへの恐怖心を無くすために文字に見慣れる必要があると感じ、Twitterなどで自身も発していこうと決めた。

### 参考文献リスト

https://docs.google.com/spreadsheets/d/1-Szgzto-OSchk3K4-7QGuvwWY_zkJWc150O0qoTAhrg/edit#gid=0

********

### 中間発表スライド

https://docs.google.com/presentation/d/1Kapit6zKgKVutjfvIrUSKxH68EmtHBFG_Y533dzR4KI/edit#slide=id.g100ed316993_0_0

### 最終発表スライド

https://docs.google.com/presentation/d/1WUNLvuxUK2IOrlYOxTdbF8h4oNLbWbUOtM0n-deJsT4/edit?usp=sharing

### GitHubレポジトリ

[2022年度スタート予定の【地理・歴史】高等学校新学習要領リポジトリ](https://github.com/furuhashilab/courseofstudy4highschool2022japan)

### プロジェクト管理

[2021gsc_ShioriOnoプロジェクト](https://github.com/furuhashilab/sotsuron2021/projects/25)

