This is the Japanese version of [Discover Meteor](http://discovermeteor.com).

Check it out live at http://ja.discovermeteor.com/

## 翻訳への参加方法
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/DiscoverMeteor/DiscoverMeteor_Ja?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[レポジトリにissueを追加](https://github.com/DiscoverMeteor/DiscoverMeteor_Ja/issues/new)し、 @SachaG 宛てに参加の意志を伝えてください。英語版のソースへのアクセス権をもらうことができます。

## 翻訳ガイドライン

[https://www.discovermeteor.com/guidelines](https://www.discovermeteor.com/guidelines)より抜粋

### 翻訳対象について

 * 各ファイルの先頭にある `---` に囲まれた領域 (YAML frontmatter) は変更しないようにしてください
   * `title` `content` `version` は変更して大丈夫です
 * 英語版レポジトリに含まれているファイルのみ翻訳するようにしてください (extra chaptersは翻訳しないように)

### 便利情報

 * 最終的な見た目を手元の環境で確認したい場合、[Discover Meteor Static](https://github.com/DiscoverMeteor/DiscoverMeteorStatic)を使ってみてください
 * GitHub上でもファイルを編集できます
 * [公開版](http://ja.discovermeteor.com/)に各章の進捗が出ているので、残り作業の目安にしてください

### 他の人と作業が重複しないためにできること

 * 新しいファイルの翻訳を始める時に、GitHubに新しいissueまたはプルリクエストを追加しておく
 * コミットとプッシュを頻繁におこなう
 * 作業を始める前にプルしておく

### 実際の翻訳作業にあたって

 * レイアウトや見た目はなるべく原文に近づけるようにお願いします
 * とはいえ、日本語としてすんなり読めるようにおおいに編集してください

### その他

 * 質問があれば[チャット](https://gitter.im/DiscoverMeteor)かGitHub issuesへ

## 原文のバージョンとの対応付けについて

日本語版レポジトリでは、ファイルの先頭にあるメタデータに、`version: x.x` という形で対応する原文のバージョンを記録しています。

バージョン番号は[Changelog](https://github.com/DiscoverMeteor/DiscoverMeteor_En/blob/master/b-changelog.md.erb)ファイルに記録されている 1.7 などの数字を使います。そのバージョンの原文は、GitHub上からだと下のスクリーンショットにあるドロップダウンメニューで、該当する「Tag」を選ぶことで見ることができます。

![Tag dropdown](https://cloud.githubusercontent.com/assets/21108/4913481/a0dd4238-64b2-11e4-828b-4fba6339be75.png)

翻訳する時や修正する時は、対応する英語版のソースを参照するようにしてください。

- 新規に翻訳を始める時は、最新バージョンをベースにする
- バージョンを更新する時は、対象ファイルの元バージョンと最新バージョンの差分を見ながら変更を反映する
- 翻訳・更新が終わったら `version: x.x` を更新する

差分はGitHub上で確認できます。例えばバージョン 1.7 と最新版の差分は以下のURLで見られます:

https://github.com/DiscoverMeteor/DiscoverMeteor_En/compare/1.7...master

1.7と1.8を比較するならば、URLの最後を `1.7...1.8` とします。

コマンドラインでOKな方はもちろん `git diff 1.7 1.8` でどうぞ。
