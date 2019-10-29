# 定型メールによるメール作成支援システム

# 評価実験：
評価実験では、**よく書くメール**に似たようなメールを作成する際の通常作業と、本システムを利用して作成する作業を比べて、評価していただきます。

評価実験の流れとしては:
* システムの導入と環境の準備をします
* 以前のやり方で、過去よく書いた一場面を基づいて、５通以上の似たようなメールを作成します
* 今度、本システムを通じて、同じ場面で、５通以上の似たようなメールを作成します
* 以前の作業と比べて、本システムを用いたやり方を評価します

## システムの導入と環境の準備
* このGithubのレポジトリから本システムをダウンロードできます
* メールデータを、"backup"というフォルダに置きます

## 過去よく書いた場面に、似たようなメールを作成するときによくある作業
<!-- 例として、あなたは社会人で、毎日、ほぼ同じ仕事を上司に報告メールを送らなければなりません。そのメールを作成するたびに、
* 送信メールボックスに入って、検索バーに、過去メールに書かれたと思う単語を入力して、検索する。
* 検索結果の中、件名またメールの最初行から適切そうなメールを判断して、メールを開いて、そのメールの文章をコピーします。
* 作成画面に入って、コピーした文章を貼り付けます。
* 内容を修正して、送信します。-->

メールテンプレート作成方法（Gmail）：https://support.google.com/a/users/answer/9308990?hl=en

## 本システムの使い方
* WindowsのCommand PromptやMacのTerminalを開いて、下記のコマンドでシステムを起動できます<pre><code>python main.py</code></pre>
* 上のメニューバーにある"メール作成"を選んで、"キーワード入力"を選ぶと、検索画面が出ます
* 作成したい場面に関する単語を入力して、"検索"ボタンを押すと、定型メールのデータベースから検索できます。検索単語は複数の場合、"、"で区切ります
* 出てきた検索結果について、各定型メールの上の方は件名で、下の方はそのメールの重要な単語です。
* 該当する定型メールをクリックすると、メール作成画面に移行します
* メール作成場面で、文章を修正して、宛先と件名を入力して、"送信"ボタンを押すと、作成したメールを送信できます


* 上のメニューバーにある"データベース"を選んで、"定型メール"を選ぶと、定型メールのデータベースを見ることができます
* 同じく、"全メール"を選ぶと、全ての送信メールが表示されます
* Tip: 開いているwindowを閉じたいとき、"Esc"キーを押すだけ！


## 評価方法
・アンケート：https://docs.google.com/forms/d/e/1FAIpQLSeJwLYg_dIfULRmdU7JYV1z23kIhBUxhj3c6zkuYOJK0SLt3Q/viewform?usp=sf_link
