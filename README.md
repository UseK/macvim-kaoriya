「**[MacVim](http://code.google.com/p/macvim/) ＋ [香り屋さんのパッチ](http://www.kaoriya.net/software/vim/) ＋ なるべく日本語化 ＝ 香り屋さんのWindows版の使い勝手に近いMacVim**」を**勝手に**目指すプロジェクトです。

[![](http://splhack.github.io/macvim-kaoriya/macvim-kaoriya-s.png)](http://splhack.github.io/macvim-kaoriya/macvim-kaoriya.jpg)

## お知らせ ##

**またMacVimか** と嘆かれる前に、[GitHub Issues](https://github.com/splhack/macvim-kaoriya/issues)や[twitter](http://twitter.com/splhack)などに報告いただけますと大変うれしいです。

**Mac OS X 10.8/10.9/10.10用バイナリは [GitHubリリース](https://github.com/splhack/macvim-kaoriya/releases/latest) からダウンロードできます。**

## MacVim ##

マルチウインドウが使えるMac OS XアプリケーションのVim(GVim)です。GUIを担当するMacVimと、Vim本体から構成されています。Vim本体はコンソールアプリケーションとしても使用できます。

## 香り屋版 ##

日本語を扱う上で便利な設定やスクリプトが追加されています。ローマ字のまま日本語をインクリメンタル検索できるmigemo機能が統合されています。詳しくは[こちら(http://d.hatena.ne.jp/thinca/20090619/1245338963)](http://d.hatena.ne.jp/thinca/20090619/1245338963)をご覧ください。

## MacVim-KaoriYa ##

MacVimに対して、香り屋パッチの統合、ローカライズ、MacVim固有の設定、日本語文字コード自動判別、必要なshared library、Perl/Python/Rubyのdynamic loading、Objective-C対応ctags、などを追加しています。[詳しくはこちらのページにまとめてあります](DiffMacVimVsMacVimKaoriYa.md)。インストールしてすぐ使えるのが目標です。もちろんTerminal.app、iTerm.app上で動くコンソール版Vimとしても使用できます。

詳しくはドキュメント「[はじめにお読みください](Readme.md)」をご覧ください

## インストール ##

[MacVim-KaoriYa GitHubリリースページ](https://github.com/splhack/macvim-kaoriya/releases/latest)からdmgファイルをダウンロードして、dmgファイルを開きます。MacVimアイコンをアプリケーションフォルダにドラッグするだけでインストール完了です。

## アップデート ##

MacVimに組み込まれた[Sparkle](http://sparkle.andymatuschak.org/)によるアプリケーション自動更新機能があり、[Sparkle用のfeed](http://macvim-kaoriya.googlecode.com/svn/wiki/latest.xml)を自動または手動で確認して、アプリケーションを更新することができます。

手動で行う場合は、インストール時と同じくMacVimアイコンをアプリケーションフォルダにドラッグして、上書きコピーすれば完了です。

## ドキュメント ##

[はじめにお読みください](Readme.md)

## ソースコードからのビルド ##

[ビルド方法のページ](Building.md)