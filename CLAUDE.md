# プロジェクトルール

## 変更時のルール
- ファイルを変更したら、毎回GitHubにコミット＆プッシュする
- PDFを再生成して確認できるようにする

## ビルドコマンド
```bash
docker compose run --rm review && open articles/AIデバイス未来考察.pdf
```

## ファイル構成
- `articles/ai-device.re` - 本文（Re:VIEW形式）
- `articles/config.yml` - 設定ファイル
- `articles/catalog.yml` - 章構成
