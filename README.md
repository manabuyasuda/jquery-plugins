# jquery-plugins
よく使うjQueryプラグインとスクリプト


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

## [Minigrid](https://github.com/manabuyasuda/jquery-plugins/wiki/Minigrid)
### インストール
* <a href="https://github.com/henriquea/minigrid">henriquea/minigrid: Minimal 2kb zero dependency cascading grid layout</a>
* `npm install minigrid`
* `//cdnjs.cloudflare.com/ajax/libs/minigrid/2.0.0/minigrid.min.js`

### 特徴と注意点
* 「Pinterest」のような高さが揃わないタイルUI
* 親要素と子要素のclass属性を指定する
* ミニファイした状態で2KB
* アニメーションの拡張は<a href="http://julian.com/research/velocity/">Velocity.js</a>に依存する
* CSSの`transition`プロパティでもアニメーションできる

## [imageSwitch.js](https://github.com/manabuyasuda/jquery-plugins/wiki/imageSwitch.js)
### 特徴と注意点
* 自作スクリプト
* jQueryで画像の`src`属性の値を一部変更して画像置換をする
* ウィンドウサイズに応じて動的にも切り替わる

## [scrollNav.js](https://github.com/manabuyasuda/jquery-plugins/wiki/scrollNav.js)
### 特徴と注意点
* 自作スクリプト
* 下にスクロールすると要素が非表示になり、上にスクロールすると表示される
* 要素の固定と表示はCSSで指定する

## [Colorbox](https://github.com/manabuyasuda/jquery-plugins/wiki/Colorbox)
### 特徴と注意点
* モーダル
* グループ化ができて、モーダル間を移動できる