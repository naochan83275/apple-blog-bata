---
layout: post
title:  "Apple のフォントをwindowsで使用する"
---

# Apple のフォントをwindowsで使用する

皆さん、初めまして。

Naochan、と申します。

本記事では、<strong>Appleのフォント(SF Pro)をWebフォントとして利用する方法</strong>を解説していきたいと思います。

## 注意事項

* SF Pro は、商用利用ができません。あくまでも開発目的だけで使いましょう。

  (え、このサイトに使っても良いのかって? いや、このサイトは開発目的で作っているから大丈夫大丈夫...)

## 使用するソフトウェア

* 7-zip
* Meiryo UI も大っきらい!!

## 手順

①7-zipをダウンロード、インストールする

* [公式サイト](https://7-zip.org/)からダウンロードします。
* ダウンロードしたインストーラーを起動し、7-zipをインストールします。

②Meiryo UI も大っきらい!! をダウンロードする

* [Tatsu ミュージアム](https://www.tatsu-syo.info/MySoft/WinCust/index.html#DLnoMeiryoUI)からMeiryo UI も大っきらい!! をダウンロードします。
* ダウンロードした.zipファイルは展開しておくとよいでしょう。

③SF Pro をダウンロードする

* [Apple Developer](https://developer.apple.com/fonts/)から SF Pro をダウンロードします。

④SF-Pro のttfファイルを抽出する

* 7-zipでダウンロードした SF-Pro.dmg を開き、その中の"SF Pro Fonts.pkg"を開きます。
* さらにその中の"Payload~"を開きます。"."を開き、その中の"Libraly"を開きます。
* "Fonts" 内の下の方にある SF-Pro.ttf が目当てのファイルです。このファイルをコピーしておきましょう。

⑤SF Pro をインストールする

* 手順④でコピーした SF-Pro.ttf を開き、[インストール]を押します。
* フォントがインストールされるのを待ちます。

⑥Meiryo UI も大っきらい!! でフォントを設定する

* 手順②で展開した.zipファイルを開き、nomeiryoui.exeを開きます(管理者権限が必要です)
* [一括変更]のところを、SF Pro (medium,お好きなサイズ)にし、[一括変更して終了]をクリックします。

これで適用されたはずです。

説明が下手ですが、最後まで読んでくださりありがとうございました。
