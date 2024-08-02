
<!DOCTYPE html>

<html lang="ja">
   
<head>
   
<meta charset="UTF-8">
   
<title> Web開発の練習１</title>
   <link rel="stylesheet" href="mystyle.css">

<script src="myjs.js"></script>
   
</head>
   
<body>
   
<!--文字の大きさの練習-->
   
<h1>練習問題2.2</h1>

<h1>Hello World</h1>
　<h2>Hello World</h2>
　<h3>Hello World</h3>
　<ol>
    
　 <li>ほげほげ</li>
    
   <li>ほにゃらら</li>
    
</ol>
   
</body>
   
</html>

<h1>練習問題2.3</h1>

<dl>
<dt>作者</dt>
<dd>ジョン</dd>
<dd>ポール</dd>
<dd>ジョージ</dd>
<dd>リンゴ</dd>
</dl>

<dl>
<dt lang="ja"><dfn>色</dfn></dt>
<dt lang="en-US"><dfn>color</dfn></dt>
<dt lang="en-GB"><dfn>colour</dfn></dt>
<dd>可視光線の波長の長短によって人が視覚で感じ 分けられる色覚・色刺激のこと.</dd>
</dl>
<p>ゲームの得点は以下の順序で計算されます。
</p>
<dl>
<dt>金貨を獲得している場合</dt>
<dd>金貨一枚につき１０ポイント加算されます。
</dd>
<dt>銀貨を獲得している場合</dt>
<dd>銀貨一枚につき１ポイント加算されます。</dd>
<dt>枚数に関わらず、金貨と銀貨の両方を獲得して いる場合</dt>
<dd>ボーナスポイントとして２０ポイント加算されます 。
</dd>
<dt>それ以外の場合</dt>
<dd>ポイントは加算されません。</dd>
</dl>

<h1>練習問題2.4</h1>

<table>
<caption>
<strong>お寿司をどこで食べるか？その長所と短所</strong>
<details>
<summary>このテーブルの説明</summary>
<p>以下のテーブルでは、２番目のカラムに寿司店のタイプが入れられ ています。その左側にそのようなタイプのお店でお寿司を食べる場合 の長所が、右側に短所が入れられています。</p>
</details>
</caption>
<thead>
<tr><th class=“important”>長所</th><th>どこで食べるか</th><th>短所
</th></tr>
</thead>
<tbody>
<tr><td>ネタにこだわり、技術が素晴らしい</td><th>銀座の高級店 </th><td>値段が時価で不安、予約が必要</td></tr>
<tr><td>値段が良心的、気軽に手に取れる</td><th>回転寿司 </th><td>ネタが解凍もの、休みの日は混む</td></tr>
</tbody>
</table>

<p class="sample1">セキュリティ対策は今後ますます重要にな るでしょう。</p>
<p class="sample2">セキュリティ対策は今後ますます重要にな るでしょう。</p>
<p class="sample3">セキュリティ対策は今後ますます重要にな るでしょう。</p>

<h1>練習問題2.5</h1>

<ul>
<li>参考資料を調べ、次のように表示されるHTMLを書きなさい。
<p
style="margin:1ex">x<sup>2</sup>+y<sup>2</sup>=z<sup>2</sup>
<br>
この授業は<b>情報特講１</b>で、<s>眠くなる</s>大変興味深い内容で す。<br>
<bdo dir="rtl">昔の日本語は右から左に書いていました。</bdo></p>
</li>
</ul

   <h1>練習問題2.6</h1>

<!DOCTYPE html>
<html lang-”ja”>
 <head>
    <meta charset="utf-8">
    <title>練習問題2.6</title>
 </head>
 <body>
    <p>テキスト入力：<input type="text"></p>
 </body>
 </html>

<h1>練習問題2.7</h1>

<form action="xxx.php" method="post"><label>メール（ type="email"）:<input type="email"
name="email"></label><input type="submit" value="送信 "></form>

<br>
<form action="xxx.php" method="post"><label>URL（ type="url"）:<input type="url" name="url"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>検索（ type="search"）:<input type="search"
name="search"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>電話（ type="telephone"）:<input type="tel"
name="tel"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>数値（ type="number"）:<input type="number"
name="number"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>日付（ type="date"）:<input type="date"
name="date"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>ローカル日時 （type="datetime-local"）:<input type="datetime-local"
name="datetime-local"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>月（ type="month"）:<input type="month"
name="month"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>週（ type="week"）:<input type="week"
name="week"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>時間（ type="time"）:<input type="time"
name="time"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>レンジ（ type="range"）:<input type="range"
name="range"></label><input type="submit" value="送信 "></form>
<form action="xxx.php" method="post"><label>色（ type="color"）:<input type="color"
name="color"></label><input type="submit" value="送信 "></form>

<h1>練習問題2.8</h1>

<p><label>名前：<input type="text" name="name" size="30" maxlength="20"></label></p>
<p><label>パスワード：<input type="password" name="pass" size="6"
maxlength="4"></label></p>
<p>学年：
<label><input type="radio" name="gakunen" value="1">１年生</label>
<label><input type="radio" name="gakunen" value="2">２年生</label>
<label><input type="radio" name="gakunen" value="3">３年生</label>
<label><input type="radio" name="gakunen" value="4">４年生</label>
<label><input type="radio" name="gakunen" value="5">５年生</label>
<label><input type="radio" name="gakunen" value="6">６年生</label>
</p>
<p>好きな課目：
<label><input type="checkbox" name="kamoku" value="kokugo">国語</label>
label><input type="checkbox" name="kamoku" value="eigo">英語</label>
<label><input type="checkbox" name="kamoku" value="sansu">算数</label>
<label><input type="checkbox" name="kamoku" value="rika">理科</label>
<label><input type="checkbox" name="kamoku" value="syakai">社会</label>
<label><input type="checkbox" name="kamoku" value="taiiku">体育</label>
</p>
<p><label>宿題ファイル：<input type="file" name="syukudai"></label></p>
<p>
<input type="submit" value="送信">
<input type="reset" value="リセット">

   <h1>練習問題3.1</h1>

<a href=“a.html”>相対パスでリンクします</a>
   <br>
<a href=https://www.josai.ac.jp/management/>絶対パスで城西大学経営学部へリンクします。</a><br>
<a href=“mailto:zm23245@josai.ac.jp”>zm23245@josai.ac.jp</a><br>
<a href=“https://www.josai.ac.jp/management/”>
<img src=“./image/keiei_small.jpg” alt=“城西大学経営学部"></a>

  <h1>練習問題3.2</h1>

<a href="a.html" target="_blank">別画面を開いてリ ンクします</a>
   <br>
   <a href="a.html" target="_self">リンク元と同じフレー ムにリンクします</a>
   <br>
   <a href="a.html" target="_parent">ひとつ上の親フ レームにリンクします</a>
   <br>
   <a href="a.html" target="_top">フレームをすべて解 除してリンクします</a>
   <br>
   <a href="a.html" target="abc">abcという名前のフレ ームにリンクします</a>
   <br>

   <h1>練習問題3.3</h1>

   <li>ほにゃらら</li>
</ol>
<a id=“abc”>ここがabcの場所</a>
<dl>
   <dt>liangjiankun</dt>
   <body>
   <p>アンカータグの練習です。</p>
      
   <a id=“def”>ここがdefの場所</a>
      
   </body>

   ファイルの途中にidでabcという名前を付けます。
   
   <a href=“#abc">abcと名前を付けた場所へリンクしま す</a><br>
   
   <a href=“a.html#def">別ファイルの名前を付けた場 所へリンクします</a>
   
   <h1>練習問題3.4</h1>

   <aside class=“ad”>
   <h1>広報</h1>
   <a href=“https://sports.josai.ac.jp/news/nid00000270.html?_ga=2.108260102.546 799402.1715649811-1950105430.1715649811”>
   <section>
   <h1> 【女子ソフトボール部】春季リーグ戦で全勝優勝！3季連続優勝を果たしました！
   </h1>
   <p> 2024年4月29日、5月3日、5月5日、東京国際大学ソフトボール場を会場に開催さ れた第19回関東学生女子ソフトボール春季リーグ戦（I部）で、女子ソフトボール部が全 勝で優勝しました。2023年度の春季リーグ・秋季リーグに続き、3季連続での優勝とな り、城西大学女子ソフトボール史上初の快挙となりました！</p></section></a>

   <a href=“https://www.josai.ac.jp/about/facility/shimokawara/”>
   <section>
   <h1>城西大学 JOSAI SPORTS FEILD </h1>
   <p> JOSAI SPORTS FIELD 【城西大学 坂戸キャンパス】</p>
   <p> 2020年9月に完成した、城西大学の新しいスポーツ施設です。サッカー場2面、ソ フトボール場1面、人工芝を敷き詰めた約1kmの周回ランニング走路を整備しました。 サッカー場の人工芝、ソフトボール場の舗装は水はけにも配慮、緩いアップダウンを付 けたランニング走路にも足に優しい人工芝を特に選んでいます。 </p>
   </section></a>
   </aside>
   
   <h1>練習問題3.5</h1>

   <nav>
   <ul>
   <li><a href=“https://sports.josai.ac.jp/club/dansiekiden/”> 男子駅伝部</a></li>
   <li><a href=“https://sports.josai.ac.jp/club/josiekiden/”>女 子駅伝部</a></li>
   <li><a>クラブ・サークル活動</a></li>
   </ul>
    </nav>



<title>Web開発の練習2023</title>
<link rel="stylesheet" href="mystyle.css"> <!-- この行を追加-->

   <h1>イベントハンドラの練習</h1>

   <input type="button"value-"ここをクリック"
   ondblclick="alert('Hello,liangjiankun');">

</dl>body
</html>
   



# web
