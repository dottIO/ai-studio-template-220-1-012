# ai-studio-template-220-1-012

詳細は「220-1-012_AI時代のシステム開発実践(チーム)_コード解説書.pdf」を参照してください。

## アプリケーションの実行

```
docker compose up --build
```

Web ブラウザで http://localhost:8080 にアクセスします。
停止はターミナルで Ctrl-C を入力します。

## コードチェック（ESLint）の実行

```
docker compose -f docker-compose-test.yml up --build
```
