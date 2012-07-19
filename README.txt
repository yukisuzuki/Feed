ＨＰの端っこにあると、便利なニュースフィード。


コピーライト

Copyright 2011, The Dojo Foundation

 (c) Copyright 2010-2011, Zazar Ltd

参照サイト

jquerytools
http://jquerytools.org/

black-flag.net
http://black-flag.net/jquery/20110228-2697.html

MEMORVA
http://memorva.jp/memo/api/rss.php

ソース解説

$(function(){
	$('#feed').rssfeed('http://suomi-neito.com/rss ',{
		limit: 9
	});
});
だけｊｓファイルに入れてないので、リンクを変えるだけでＲＳＳに対応したサイトは何でも表示できます。
limitは出てくるニュースの数です。


jquery.zrssfeed.jsと、
http://ajax.googleapis.com/ajax/libs/jquery/1.5.0/jquery.min.jsはネットからいただきました。
java.jsは最初は引用でしたが改変しすぎたので何とも言えません。
スクロールは現在調整中なので、コマ送りですが以上ではありません。よ。
ぬるぬる動くように頑張ります
