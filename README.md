# JavaScript で神経衰弱を作る！

JavaScript の DOM 操作までの基礎知識を学び終えたらそれを実践してみよう！

## 学習の始め方

作成の STEP ごとに brunch を切ってます
各 STEP における README.md の内容を参考に自分で JavaScript を書いてみて,最終的にその STEP のコードと比較してみましょう！
ここのコードは一つの解答に過ぎませんので,より良い書き方を模索したり,違った処理で実装してみても GOOD です！

## STEPS

1. トランプを並べる

   - index.html, style.css, main.js の 3 つのファイルの作成
   - トランプの配列を作成
   - その配列を使ってトランプを表示する
   - トランプがランダムに並ぶようにする

2. トランプがクリックするとオープンされるように

   - 表示されたトランプを裏にして表示
   - 裏のトランプをクリックすると表になるように
   - 3 枚目のカードをオープンすると 1,2 枚目のカードは裏になるように

3. **神経衰弱っぽく**

   - 1,2 枚目のトランプの数字が一致していた場合に,そのカードを非表示に（他のカードの位置は変えない）
   - 揃えたペアの数をカウントして表示
   - すべて消えたら Congratulations!!

4. 修繕課題

   - オープンされたカードをクリックしてもなにも起こらないように
   - 揃えたらできる空白をクリックしてもなにも起こらないように

5. 追加機能

   - ゲームスタートボタンとリセットボタンを追加
   - タイムアタックモードを追加
