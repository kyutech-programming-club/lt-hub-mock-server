# lt-hub-mock-server
LT-HubのAPIモックサーバをDockerコンテナ上に作成
## 前提条件
- Docker
- Docker Compose
## セットアップ
コンテナ作成

```
git clone git@github.com:kyutech-programming-club/lt-hub-mock-server.git
cd lt-hub-mock-server/
docker-compose up
```
作成後
```
http://localhost:8080/ahiahi
```
にアクセスしてレスポンスを確認

## Stoplight Prism
apiのモックサーバ

```
http://localhost:8080/
```
## Swagger UI
apiの仕様を確認できる

```
http://localhost:8081/
```
## Swagger Editor
仕様書を編集できる
```
http://localhost:8082/
```
ローカルのapi.yamlは更新されません
編集後, ファイルをダウンロードしてapi.yamlと差し替えてください
