[English](readme.md) | 日本語

<p align="center">
  <img src="https://github.com/Anze/KeyCluCask/blob/main/img/keyclu.png?raw=true" height="128" />
  <h1 align="center">KeyClu for macOS</h1>
</p>

アプリのショートカットなどを簡単・便利に一覧表示できます。使い方は簡単: ⌘ キーを2回押してそのまま押し続けるだけで一覧表示を見られます。

![platform:macos  + Intel](https://img.shields.io/badge/platform-macOS%20%20%20+%20Intel-2F3640.svg)
![version:bigsur](https://img.shields.io/badge/requirements-Big%20Sur%2B-337AFF.svg)
![category:productivity](https://img.shields.io/badge/category-productivity-blue.svg)
![license:bsd-3-clause-clear](https://img.shields.io/badge/license-BSD--3--Clause--Clear-orange.svg)

[![github downloads](https://sergii.tatarenkov.name/apps/keyclu/github-downloads.svg)](https://github.com/Anze/KeyCluCask/releases/latest)
[![brew installs](https://sergii.tatarenkov.name/apps/keyclu/brew-downloads.svg)](https://formulae.brew.sh/cask/keyclu)
[![crowdin](https://badges.crowdin.net/keyclu/localized.svg)](https://crowdin.com/project/keyclu)

## スクリーンショット
![screenshot1](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_1.png)

![screenshot2](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_2.png)

![screenshot3](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_3.png)

## インストール方法
### Homebrew
Homebrew を使ってインストールするには、ターミナルアプリを開いて、次のようにに入力します：
```
brew install --cask keyclu
```
### 手動インストール
まず [最新版](https://github.com/Anze/KeyCluCask/releases/latest) `.dmg` をダウンロードします。次にそのファイルを開いて KeyClu アプリをアプリケーションフォルダに移動させてください。

## 権限
* 操作するには `アクセシビリティ API` へのアクセスが必要です。
* `通知センター` へのアクセスは、優しい更新通知のために推奨されます。

## 基本的な使い方
* `⌘` キーを 2 回押してそのままキーを長押しするとと現在のアプリのショートカットを表示します (既定値)。
* `⌘` キーを 1 回押して押し、そのままキーを長押しすると、現在のアプリのショートカットを表示します（代替）。
 
## 機能
* 希望に合わせて表示を調整できます
* 外観を `システム`、`ライト` そして `ダーク`に変更
* ショートカットをブックマーク
* 分かっているショートカットを非表示
* ショートカットのグループ（メニュー） の折りたたみ
* アプリのショートカットをマークダウン形式のファイルに書き出し
* macOS ホットキーを表示
* macOS ジェスチャを表示
* skhd ホットキーを表示
* Jitouch2 ジェスチャを表示
* 自分で定義したショートカットを表示

## 機能
* [CustomShortcuts](https://www.houdah.com/customShortcuts/) ショートカットカットをカスタマイズできます。
* [skhd](https://github.com/koekeishiya/skhd) でショートカットを一覧表示できます。詳細は [skhd wiki ページ](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-skhd) をご参照ください。
* CLI パラメータ。詳細は [CLI param wiki ページ](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-CLI-params) をご参照ください。

## よくある質問と解答
### アイコンが非表示の場合、設定を開くにはどうすればよいですか？
設定画面を開くには、アプリを再度起動してください。

### アプリがクラッシュしてしまいました！
クラッシュが発生した場合は、課題を開き、詳細、関連するログ、およびクラッシュにつながった可能性のある操作の簡潔な説明をご提供ください。問題に必要な情報を収集するためのガイダンスとして、よくある質問のページ [FAQ - KeyClu just crashed](https://github.com/Anze/KeyCluCask/wiki/FAQ#keyclu-just-crashed) をご確認ください。ご協力いただくことで、問題をより効果的に解決できるようになります。

## ロードマップ
[KeyClu のプロジェクトボード ](https://github.com/users/Anze/projects/1)をごらんいただき、何が進行中なのかをご確認ください!

機能リクエストはいつでも大歓迎です。

## プライバシー方針
KeyClu は個人情報を収集しませんし、分析や宣伝などの目的でいかなるサービスも使用しません。

## ライセンスとクレジット
KeyClu は BSD-3-Clause-Clear ライセンスの下でリリースされています。詳細は [ライセンス](LICENSE) をごらんください。

このソフトウェアは以下のオープンソースパッケージを使用しています：
* [Sparkle](https://github.com/sparkle-project/Sparkle)
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift)
* [SQLiteMigrationManager.swift](https://github.com/garriguv/SQLiteMigrationManager.swift)
* [JSON.swift](https://github.com/mikezs/Tisander)

## 多言語化
以下の貢献者の翻訳作業に多大な感謝を申し上げます：
* ja-JP: [@9demaio1964](https://github.com/9demaio1964)

## 謝辞
* ご協力いただいた皆様に感謝いたします
* 感谢 [@wanwindwalker](https://github.com/wanwindwalker) 従来のアプリアイコンをデザインしてくださった

## サポート
もし KeyClu を❤️して、タスクに役立ったと感じたら、ぜひ ⭐ して、カフェインで応援してくださいね。
