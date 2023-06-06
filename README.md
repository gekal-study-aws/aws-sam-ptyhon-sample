# Lambda(Python)のサンプル

## プロジェクトの作成

```bash
sam init --name aws-sam-ptyhon-sample --runtime python3.10
```

## プロジェクトのビルド

```bash
sam build --use-container
# コンテナを利用するため、Dockerのインストールを確認してから実行してください。
```

## アプリのテスト

```bash
sam local invoke HelloWorldFunction --event events/hello.json
```
