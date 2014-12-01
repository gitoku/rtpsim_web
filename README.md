rtpsim_web
=========


構成
---

### フォルダ
* rtp_img
	* 画像ファイルはだいたいここ
* lightbox
	*  [lightbox2](http://lokeshdhakar.com/projects/lightbox2/)
* bootstrap
	* [bootstrap](http://getbootstrap.com)
* css
	* [flat-ui](http://designmodo.github.io/Flat-UI/)
* js
	* [flat-ui](http://designmodo.github.io/Flat-UI/)

### ページ
* rtp.html
	* メインのページ
* rtp_howto.html
* rtp_install.html

### その他ファイル
* RTPSim.pdf
	* 研究説明pdf
* RTPsim_v20141023.zip
	* RTPsim配布ファイル
* movie_conte.pdf
	* 動画コンテ

### 使用framework
* [flat-ui](http://designmodo.github.io/Flat-UI/)
	* フラットデザイン用テンプレート
	* 今回はこのテンプレートに含まれるサンプルを元にcssを記述
		* おもな変更は`css/demo.css`
* [bootstrap](http://getbootstrap.com)
	* cssフレームワーク(flat-uiより参照)
* [lightbox2](http://lokeshdhakar.com/projects/lightbox2/)
	* 画像の自動拡大縮小とlightbox表示

その他注意
--------

* lightboxによって各画像はページ内の親要素(もしくはブラウザウィンドウ)の幅まで拡大・縮小される
* 各ページでは内容を節ごとに`<div class="tile">`で囲っているので、必要があれば利用する
* 各ページではコンテンツ全体を`<div class="container">`で囲っている。現在はコンテンツの幅指定の用途で用いている。
* lightboxをフォルダごと削除すれば、画像ファイルのリンクはただの画像リンクとして扱われる

### flat-ui改造部分について

