## コンテナ起動、イメージ作成

ルートディレクトリ(ここではリポジトリ名である adoption)に移動し、

```
docker-compose up -d
```

を powershell 等で実行

### バックエンドコンテナアクセス方法

```
docker exec -it backend /bin/sh

```

### フロントエンドコンテナアクセス方法

vscode 上でコンテナにアタッチ
