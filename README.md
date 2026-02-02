# Schedule App 📅

シンプルで美しく、高機能なスケジュール管理アプリケーション。
フレームワークなしのVanilla JSで構築されており、ブラウザのLocalStorageを使用してデータを保存します。
<img width="2428" height="1413" alt="image" src="https://github.com/user-attachments/assets/8287803b-9e86-4172-ba45-aa48bde2b2d8" />



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
- **Antigravity**: AIエージェントを活用し、設計検討・コード生成・改善を行いながら開発

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
## 　 参考コード
<img width="1761" height="1530" alt="image" src="https://github.com/user-attachments/assets/c3427c71-5d5d-463f-b6b9-1a3be95a6729" />






