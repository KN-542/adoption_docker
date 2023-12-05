## コンテナ起動、イメージ作成

ルートディレクトリ(ここではリポジトリ名である adoption)に移動し、

```
docker-compose up -d
```

を powershell 等で実行

### バックエンドコンテナアクセス方法

```
docker container logs -f --tail=100 backend

```

### フロントエンドコンテナアクセス方法

vscode 上でコンテナにアタッチ
