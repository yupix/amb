# 1.2.5

## long time no see

### 機能の追加

    * vcheck時にJMusicBotのアップデートを確認するように

### 不具合の修正

    * newstartでJARが不足している際、ダウンロードで不正なキー入力を受け付けた際の動作を修正
    * newstartでe以外のキーを押した際、最初から起動する不具合の修正
    * newstartで既に起動している状態で、動かすとjavaが大量起動される不具合の修正

### 仕様の変更など

    *newstartでjarが不足時、ダウンロード中のspinnerの作成
    *newstartでspinerが全体的に高速化
    *newstartでファイル作成に失敗した際用に、リトライ上限を設定
    *newstartをnewstartに変更
    *setSettingsで１つ設定が終わった後に設定を更新して再表示するように変更
    *newstartの

### 今後の予定

    * 文字の変数化
    * 新起動方法の正式実装

### 注意点

    * 全ての機能の安定した動作を確認できていません
    * 最近追加されたコードには多くの不具合が含まれる可能性があります。
    * newbotstartコマンドは不安定でテスト中の為、非推奨です。

### 詳しい変更点は以下のサイトまで

    * https://akarinext.org/wordpress/

# 1.2.4
### 不具合の修正
    * startコマンドを実行した際のバージョンチェックをキャンセルした際その時点で、Botをスタートする実装を修正
    * Jarファイルのダウンロード後、ファイルを別のディレクトリーに移動させる処理が無かった為修正
### 仕様の変更など
    *JMusicBotのバージョンを0.2.7に正式対応
### 今後の予定
    * 文字の変数化
    * 新起動方法の正式実装
### 注意点
    * 全ての機能の安定した動作を確認できていません
    * 最近追加されたコードには多くの不具合が含まれる可能性があります。
    * newbotstartコマンドは不安定でテスト中の為、非推奨です。

# 1.2.3
### 不具合の修正
    * 新バージョンを記載したファイルのダウンロードを行わないようになっていた為修正
    * setSettingsの不正なキー入力を受付ないよう大幅な修正
    * botstartでファイルが存在しない場合ファイルを作るようになってなかったのを修正
### 使用の変更など
    * Botstartの中を作り直し
    * newbotstartを本バージョンから正式採用
    * reconfigを作り直し
### 今後の予定
    * 文字の変数化
### 注意事項
    * 全ての機能の安定した動作を確認できていません
    * 最近追加されたコードには多くの不具合が含まれる可能性があります。

# 1.2.2
## 機能の追加
    *拡張機能の有効化などを追加
    *開発者向け機能の追加
    *その他多数の機能の追加
### 不具合の修正
    * 初回起動時に不正なキー入力を受け付けないように
    * reconfigでのおかしな動作
    * removedevの大幅な修正
    * VersionCheckの大幅な修正
    * startコマンドの大幅な修正及び作り直し
    * autoreconfig(内部で動いてるもの)が出力する結果が逆になっていたのを修正
### 注意事項
    * 全ての機能の安定した動作を確認できていません
    * Windowsでの動作は開発者が動作確認を行ったため、動かない可能性あり
### 今後の予定
    * 文字の変数化
    * setSettingsの不正な入力を受け付けないように対策する予定
    * AMBPROJECTのアップデートをやめ、様々な機能を付けた統合版を作る予定

# 1.2.1
## 機能の追加
    *現在時刻表示機能の追加
    *開発者向け機能の追加
    *その他多数の機能の追加
### 注意事項
    * 全ての機能の安定した動作を確認できていません
    * Windowsでの動作は一部のユーザーで確認したため、動かない可能性有り
### 今後のアップデート予定
    *文字の変数化

# 1.2.0
## ファイルの追加
    *settings.txtの追加
    *windows.batの追加
## 機能の追加
    *Configの生成に失敗した場合、リトライするか否かを問う機能
    *招待リンクを自動生成する機能を追加
    *起動する際に招待リンクを表示するか否かをsetSettingsで変更可能に
    *VercheckをBOTを起動した際に自動で動かすか否かの設定の追加
    *その他細々した所の修正
### 注意事項
    * 全ての機能の安定した動作を確認できていません
### 今後のアップデート予定
    *Windowsをサポートする予定?
    *BOT本体のアップデートを確認する機能

# 1.1.5
## ファイルの追加
    * Discord フォルダを作成しました
    * Music フォルダを作成
    * variable ファイルを作成
    * CHANGELOG.mdの追加
## 機能の追加
    *Discordフォルダの自動生成機能を追加
    *Musicフォルダの自動生成機能を追加
    *ファイルの有無を確認する機構を作成
### 注意事項
    * 全ての機能の安定した動作を確認できていません
### 今後のアップデート予定
    *helpコマンドを追加
    *helpコマンド用の変数を使用できるように改善

# 1.0.0_patch-1.1.0
## ファイルの整理
    * txt関係のファイルを整理しました
    * 紫色をなぜか緑と書いていた所を修正
    * その他細々した所の修正又は翻訳の追加
## 既存のバグ
    *現在実行するとファイルの多くが存在しないと表示されます
    *現在うまくスタートしたとしても、MusicBotを起動することはできません
### 注意事項
    * ShellScriptでBotが起動しません
    * ファイルの生成機能などが存在しないため、様々な不具合が発生します

# 1.0.0
## ファイルの追加
    * 本体のShellを追加
    * その他必要性のあるファイルを追加
## 既存のバグ
    *現在実行するとファイルの多くが存在しないと表示されます
    *現在うまくスタートしたとしても、MusicBotを起動することはできません
### 注意事項
    * ShellScriptでBotが起動しません
    * ファイルの生成機能などが存在しないため、様々な不具合が発生します