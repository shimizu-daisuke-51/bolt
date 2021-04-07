

# Bolt PC
## 修正内容
--- 例 ---
1. 修正指示を記載します(メンター)
  - 修正内容を記載してください(研修生)
    例) 〇〇クラスに××を指定して△△になるようにしました。
----------

## 全体的な修正
1. 各セクションごとのpaddingを取る要素は、 `xxx-inner` で統一しましょう！
   現状は子要素のタイトルやテキストでとっていたりと、統一感がありません。
   →56行目“down-text”を“down-inner”と
   73行目“circle-text”を“circle-text-inner”に変更しました。

2. HTML構造がおかしいかな！giztechに参考が書いてあるので確認しましょう(画像添付します)
   また、HTMLの閉じタグの消し忘れの可能性があるので確認してみてください！
   →18行目のdivに閉じタグがなかった為、
   28行目に追加しました。


## bolt theme
1. タイトルとテキストの隙間はmarginです
→CSSをmaegin-topに変更しました。


## what we can do?
1. `WHAT WE CAN DO?` は見出しなので、 h2タグを使いましょう！


## OUR LATEST WORK
1. ここも `OUR ~` は見出しなのでh2タグ！
→３７行目のdivタグをh2タグに変更しました。

2. HTML構造が変ですね！ `.inner` の中に全て入れましょう！
   ```html
   <article>
     <div class="inner">
        <div class="OUR-LATEST...">
        <div class="down-text">
    </div>
    ...
  ```
  →全てinnerの中に入れました。


## OUR SKILLS
1. ここも `.inner` の中にいれましょう！
→全てinnerの中に入れました。
