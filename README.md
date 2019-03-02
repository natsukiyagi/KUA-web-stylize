# Google Chrome拡張機能「ANEMO Print Stylize」

![](https://img.shields.io/github/license/mashape/apistatus.svg)

京都造形芸術大学通信教育課程のwebマガジン『アネモメトリ』の特集を印刷する時に、印刷用にスタイリングをするGoogle Chrome拡張機能です。
ヘッダーやフッターなど、メインコンテンツ以外を非表示にし、本文のフォントサイズを大きくします。

**メリット**

- 表示しているwebページのURLが `https://magazine.air-u.kyoto-art.ac.jp/feature/*` の時に、印刷用のCSSを読み込むだけしかしていないので、『アネモメトリ』の特集を印刷をする時にしか変化が起きない
- 自動でプラグインのアップデートがされることがないので、廃止される心配・プライバシーの心配がない

**デメリット**

- 自動でプラグインのアップデートがされない
- 導入が若干面倒くさい
- 他のユーザーが作成したCSSをワンクリックで導入することはできない

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
