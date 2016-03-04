# jquery-plugins
よく使うjQueryプラグイン


## [smooth-scroll](https://github.com/manabuyasuda/jquery-plugins/wiki/smooth-scroll)
### インストール
* [smooth-scroll](https://github.com/cferdinandi/smooth-scroll)
* `npm install cferdinandi/smooth-scroll`
* `bower install https://github.com/cferdinandi/smooth-scroll.git`

### 特徴と注意点
* `data-scroll`属性をつけた要素が対象になる
* ナビゲーションを固定している場合は`selectorHeader`属性をつける
* `body`要素に`height`を指定すると不具合が起きる
* jQuery依存なし

### 参考リンク
* <a href="https://syncer.jp/how-to-make-smooth-scroll-without-jquery">スムーススクロールを実装する方法(ページ内をゆっくり移動)</a>

## [jquery.matchHeight.js](https://github.com/manabuyasuda/jquery-plugins/wiki/jquery.matchHeight.js)

### インストール
* [jquery.matchHeight.js](https://github.com/liabru/jquery-match-height)
* `npm install jquery-match-height`
* `bower install matchheight`

### 特徴と注意点
* 横並びしている要素の高さを揃える
* リサイズしたときに再計算する
* ボックスモデル、`display`や`visibility`といったプロパティも計算する
* jQueryに依存する

### 対応ブラウザ
IE8+, Chrome, Firefox, Safari, Android, iOS