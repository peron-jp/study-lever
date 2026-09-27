勉強レバー PWA ファイル一式

内容:
- index.html: アプリ本体
- manifest.json: ホーム画面追加時のアプリ設定
- service-worker.js: キャッシュによるオフライン対応
- icon.svg: アプリアイコン

公開方法（GitHub Pages）:
1. GitHubで新しい公開リポジトリを作成
2. このZIPを解凍し、中の4ファイルをリポジトリの直下にアップロード
3. Settings → Pages → Deploy from a branch → main / (root) → Save
4. 発行された https://...github.io/.../ をAndroidのChromeで開く
5. Chromeの︙メニュー →「アプリをインストール」または「ホーム画面に追加」

注意:
- PWAのインストールにはHTTPSでの公開が必要です（GitHub PagesはHTTPS対応）。
- 勉強記録はブラウザのlocalStorageに保存されます。ホーム画面アプリと通常のブラウザで保存領域が別になる場合があります。
- このZIPは静的ファイル一式です。GitHubへのアップロード・公開操作は利用者側で行ってください。
