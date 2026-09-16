# 柿込2D Animation Studio

GitHub Pagesでそのまま公開できる2Dアニメーション制作ツールです。

## GitHub Pagesへの公開
1. このフォルダの中身をGitHubリポジトリのルートへアップロードします。
2. `index.html` がリポジトリ直下にあることを確認します。
3. GitHubの **Settings → Pages** を開きます。
4. **Deploy from a branch** を選び、公開するブランチ（通常は `main`）と `/ (root)` を指定して保存します。
5. 数分後、GitHub PagesのURLから `index.html` が開けます。

## 文字化け対策
HTMLはUTF-8のまま保存し、ファイル名もUTF-8としてZIP化しています。日本語ファイル名に依存せず、GitHub Pagesの入口を `index.html` にしています。

## 注意
このアプリは外部サーバーを必要としない単一HTML構成です。ブラウザで `index.html` を開いても動作します。
