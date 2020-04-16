# Google Chrome拡張機能「KUAD Web Stylize」

![](https://img.shields.io/github/license/mashape/apistatus.svg)

学校法人瓜生山学園京都芸術大学通信教育部の芸術教養学科で学ぶ際に使用するwebサイトを、少しだけ見やすくスタイリングし直す、Google Chrome拡張機能です。

**メリット**

- 表示しているwebページのURLが特定のサイトのページの時に、CSSを読み込むだけしかしていないので、特定のサイトでしか変化が起きない
- 自動でプラグインのアップデートがされることがないので、廃止される心配・プライバシーの心配がない

**デメリット**

- 自動でプラグインのアップデートがされない
- 導入が若干面倒くさい
- 他のユーザーが作成したCSSをワンクリックで導入することはできない

## Feature

**京都芸術大学通信教育課程のwebマガジン『アネモメトリ』**

- 「特集」記事の印刷した後、少しだけ読みやすくする
  - ヘッダーやフッターなど、メインコンテンツ以外を非表示
  - 本文のフォントサイズを大きく

**ブリタニカ・オンライン・ジャパン**

- サイト全体を少しだけ見やすくする
  - サイトをディスプレイの真ん中に表示する
  - フォントの変更
  - フォントサイズを大きく

**学科内SNS「airUコミュニティ」**

- 最新書き込みの一覧リストを少しだけ見やすくする
  - フォントサイズを大きく
- 日記やコミュニティトピック、コミュニティイベントの本文とコメント部分を少しだけ見やすくする
  - フォントサイズを大きく
  - 行間を広げる
  - 文字同士のスペースを空ける
- 日記やコミュニティトピックのコメント投稿フォームを少しだけ見やすくする
  - フォントサイズを大きく
  - 行間を広げる
  - 文字同士のスペースを空ける

## Usage

1. [ZIPをダウンロード](https://github.com/natsukiyagi/anemo-print-stylize/archive/master.zip)し、任意の場所に解凍する
1. Google ChromeのURLフォームに `chrome://extensions/` を入力する
1. 右上に「デベロッパーモード」のスイッチがあるので、ONにする
1. (1)で解凍したフォルダ(註1)を、ドラッグ&ドロップする

(註1) manifest.jsonが直下に入っているフォルダ

## Author

**Natsuki Yagi（natsukiyagi）**

- [https://natsuki.yagi.osaka.jp/](https://natsuki.yagi.osaka.jp/)
- GitHub: [natsukiyagi](https://github.com/natsukiyagi)

本Google Chrome拡張機能の利用に関するいかなる被害・損害について、作者は一切の責任を負わないものとします。

## License

Copyright 2019 Natsuki Yagi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
