# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## リポジトリ概要

Web系技術記事を管理するリポジトリ。記事はWebサービス「note」で公開予定。

**対象トピック:**
- GAS（Google Apps Script）の文法・アプリ紹介
- 生成AIを使った開発
- HTML/CSS
- React / Next.js
- その他Web技術全般

## 記事作成ルール

### noteで使用可能なマークダウン記法

**見出し**
- `## 見出し` - 大見出し（h2）
- `### 見出し` - 小見出し（h3）
- h1、h4以降は使用不可（h4以降はh3に変換される）

**テキスト装飾**
- `**太字**` または `__太字__`
- `~~取り消し線~~`

**その他**
- `> ` - 引用
- `---` - 区切り線（必ず3文字で入力）
- `[リンクテキスト](URL)` - リンク
- ` ``` ` - コードブロック（言語指定でシンタックスハイライト可能）

### noteで使用不可の記法

以下の記法は使用しないこと:

- テーブル（表形式）
- インラインコード（`` `code` ``）
- 画像埋め込み（`![alt](url)`形式）
- 番号付きリスト（`1. `形式）
- 箇条書きリスト（`- `形式）のネスト

### コードブロックの書き方

言語を指定してシンタックスハイライトを有効にする:

```javascript
// このように言語名を指定する
const example = "code";
```

対応言語例: javascript, python, html, css, typescript など

## 必ず入れるメッセージ

下記のメッセージは、すべての記事の末尾に必ず追加すること

```
---

## プログラミングイベントのご案内
毎月数回、AIを活用したプログラミングを学べるオンライン講座を開催しております。直接学びたい方はぜひご参加ください。
申し込みフォームは[こちら](https://docs.google.com/forms/d/e/1FAIpQLScCLBSCJvZEl7R15tCDTajcKa7INCTSOKPEXyfIEX69Q_xtEg/viewform)
過去のプログラミングイベントの紹介は[こちら](https://sinlab.future-tech-association.org/school/)

## シンギュラリティ・ラボのご案内
オンラインサロン「シンギュラリティ・ラボ」（通称シンラボ）では、GASも含めたプログラミングをはじめ、さまざまなITスキルやチーム開発について学び、実践する場を準備しております。 初心者から経験者まで、どなたでも参加可能です。
少しでも興味がございましたらお気軽にお越しください。
シンギュラリティ・ラボHPは[こちら](https://sinlab.future-tech-association.org/join/)
お問い合わせ先 sinlab-recruit@future-tech-association.org

## GASアプリ開発サービスのお知らせ
シンギュラリティ・ラボでは、GASを中心としたWebアプリ開発のご相談を受け付けております。
普段の作業のちょっとした自動化から自分やチーム専用のカスタムアプリまで、ぜひお気軽にお問い合わせください。
詳細は[こちら](https://appdev.future-tech-association.org/)
```