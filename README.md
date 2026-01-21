# 🎳 賭けボーリング

チーム対戦のボーリング賭けゲームアプリです。スマホでも快適に使えるPWA（Progressive Web App）です。

## 🌟 機能

- ⚙️ **柔軟な設定**: 1ピンあたりのポイントを自由に設定（100ポイント、50ポイントなど）
- 👥 **無制限プレイヤー**: 各チームに何人でもプレイヤーを追加可能
- ✏️ **編集可能**: プレイヤー名もピン数も自由に編集
- 🎯 **自動計算**: チームの合計ピン数とポイントを自動計算
- 🏆 **勝敗判定**: 自動で勝敗を判定し、点差を表示
- 📱 **スマホ対応**: レスポンシブデザインでどのデバイスでも快適
- 🔌 **オフライン動作**: インストール後はオフラインでも使用可能

## 🚀 GitHub Pagesでの公開方法

### 1. GitHubリポジトリを作成

1. [GitHub](https://github.com)にログイン
2. 右上の「+」→「New repository」をクリック
3. リポジトリ名を入力（例: `bowling-bet-app`）
4. 「Public」を選択
5. 「Create repository」をクリック

### 2. ファイルをアップロード

リポジトリページで以下のファイルをアップロード:
- `bowling-bet.html`（→ `index.html` にリネーム）
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`
- `README.md`

**重要**: `bowling-bet.html` を `index.html` にリネームしてください！

または、コマンドラインで：

```bash
git clone https://github.com/あなたのユーザー名/bowling-bet-app.git
cd bowling-bet-app
# ファイルをコピー
mv bowling-bet.html index.html
git add .
git commit -m "Initial commit"
git push origin main
```

### 3. GitHub Pagesを有効化

1. リポジトリの「Settings」タブをクリック
2. 左サイドバーの「Pages」をクリック
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で「main」と「/ (root)」を選択
5. 「Save」をクリック

数分後、以下のURLでアクセス可能になります：
```
https://あなたのユーザー名.github.io/bowling-bet-app/
```

## 📱 アプリとしてインストール

### iPhone/iPad
1. Safariでサイトを開く
2. 共有ボタン（□↑）をタップ
3. 「ホーム画面に追加」をタップ
4. 「追加」をタップ

### Android
1. Chromeでサイトを開く
2. メニュー（⋮）→「アプリをインストール」または「ホーム画面に追加」
3. 「インストール」をタップ

## 💡 使い方

1. **設定**: 1ピンあたりのポイントとチーム名を設定
2. **プレイヤー追加**: 各チームに「追加」ボタンでプレイヤーを追加
3. **名前変更**: プレイヤー名をクリックして編集
4. **スコア入力**: 各プレイヤーのピン数を入力
5. **結果表示**: 「結果を計算」ボタンで勝敗を表示

## 🛠️ カスタマイズ

HTMLファイルを編集することで、色やデザインを自由にカスタマイズできます。

## 📄 ライセンス

MIT License - 自由に使用、改変、配布できます。

---

Enjoy Bowling! 🎳✨
