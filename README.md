rtpsim_web
=========


構成
---

### フォルダ
* lightbox
	* 画像の自動拡大縮小とlightbox表示
	* http://lokeshdhakar.com/projects/lightbox2/
	* jsフォルダ内にjQuery1.8.3.minを配置
* rtp_img
	* 画像ファイルはだいたいここ

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

その他注意
--------

* lightboxによって各画像はページ内の親要素(もしくはブラウザウィンドウ)の幅まで拡大・縮小される
* 各ページでは内容を節ごとに`<div class="tile">`で囲っているので、必要があれば利用する
* lightboxをフォルダごと削除すれば、画像ファイルのリンクはただの画像リンクとして扱われる
