# Premium Schedule App 📅

シンプルで美しく、高機能なスケジュール管理アプリケーション。
フレームワークなしのVanilla JSで構築されており、ブラウザのLocalStorageを使用してデータを保存します。

![App Screenshot](https://via.placeholder.com/800x450.png?text=Schedule+App+Preview)
*(必要に応じてスクリーンショットを追加してください)*

## ✨ 特徴

- **プレミアムデザイン**: ダークモード、グラスモーフィズムエフェクト、滑らかなアニメーションを採用したモダンなUI。
- **データ永続化**: サーバー不要。ブラウザのLocalStorageに予定を自動保存します。
- **直感的な操作**:
  - 月ごとのカレンダー表示
  - クリックで予定を追加・編集
  - 「New Event」ボタンからのクイック追加
- **完全レスポンシブ**: デスクトップでもタブレットでも快適に動作。
- **軽量**: 外部ライブラリへの依存なし（Google Fontsのみ）。

## 🚀 使い方

特別なインストール手順やビルドコマンドは不要です。

1. このリポジトリをクローンまたはダウンロードします。
2. フォルダ内の `index.html` をお好きなWebブラウザ（Chrome, Edge, Safariなど）で開くだけで起動します。

## 🛠️ 技術スタック

- **HTML5**: セマンティックなマークアップ
- **CSS3**: CSS変数 (Custom Properties) を活用したデザインシステム
- **JavaScript (ES6+)**: クラスベースのオブジェクト指向設計
  - `Store.js`: LocalStorage操作のラッパー
  - `Calendar.js`: カレンダー生成ロジック
  - `main.js`: イベントハンドリングとDOM操作

## 📂 フォルダ構成

```
.
├── index.html          # エントリーポイント
└── src
    ├── style.css       # デザインシステムとスタイル定義
    ├── main.js         # アプリケーション初期化
    ├── components      # UIコンポーネント
    │   └── Calendar.js # カレンダーロジック
    └── store           # データ管理
        └── Store.js    # データ永続化ロジック
```

## 📝 ライセンス

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
