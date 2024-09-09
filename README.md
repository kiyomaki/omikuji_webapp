# おみくじウェブアプリ

## 目次
- [概要](#概要)
- [動作環境](#動作環境)
- [インストール](#インストール)
- [使い方](#使い方)
- [機能](#機能)
- [依存関係](#依存関係)
- [設定](#設定)
- [貢献者](#貢献者)
- [ライセンス](#ライセンス)

## 概要
このウェブアプリは、おみくじ（日本の伝統的な運勢占い）をシミュレートするシンプルなアプリケーションです。ボタンや画像をクリックすることで運勢を引き、結果が表示され、対応する画像も表示されます。また、引いた運勢のログが記録されていきます。

## 動作環境
このパッケージは、下記の環境での動作が確認されています。
- OS: Ubuntu 22.04 LTS

## インストール
このおみくじウェブアプリをローカル環境で使用するには、以下の手順に従ってください。

1. 以下のファイルをすべてダウンロードします:
   - `omikuji.html`
   - `omikuji.js`
   - `backyard.css`
   - `center.css`
   - `log.css`
   - `word_font.css`
   - `button_font.css`
2. JavaScript内で参照されている画像ファイル（`daikichi.png`、`kichi.png` など）が同じディレクトリにあることを確認します。
3. お使いのウェブブラウザで `omikuji.html` を開いてアプリを使用します。

## 使用方法
1. `omikuji.html` ファイルをブラウザで開きます。
2. おみくじを引くには、次の方法があります:
   - 「おみくじを引く！」ボタンをクリックします。
   - または、おみくじの画像をクリックして運勢を占います。
3. 運勢がテキストボックスに表示され、対応する画像も表示されます。
4. 全ての運勢は、画面の右下にあるログパネルにリアルタイムで記録されます。

## 機能
- 以下の運勢の中からランダムで1つが表示されます: 大吉、吉、中吉、小吉、末吉、凶、大凶。
- 結果に応じて、おみくじの画像も表示されます。
- 引いた全ての運勢は、右下のログに記録されます。
- 背景画像や中央揃えのレイアウトなど、クリーンでレスポンシブなユーザーインターフェース。

## 依存関係
このプロジェクトは、以下のファイルに依存しています:
- **CSSファイル:**
  - `backyard.css`: 背景画像を設定
  - `center.css`: コンテンツを縦横中央に配置
  - `log.css`: 運勢のログを表示するパネルのスタイル
  - `word_font.css`: 全体のフォントやテキストスタイル
  - `button_font.css`: おみくじを引くボタンのスタイル
- **JavaScriptファイル:**
  - `omikuji.js`: ランダムに運勢を引いて表示し、ログを更新するロジック
- **外部ライブラリ:**
  - タイプライター風テキストアニメーション: 運勢をタイプライター風に表示

## 設定
HTMLファイルと同じディレクトリに正しい画像ファイルがあることを確認してください。

## ライセンス・著作権
- このソフトウェアは3条項BSDライセンスの下で再頒布および使用が許可されています。
- © 2024 Makishi Kiyosawa
