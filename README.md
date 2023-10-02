## コンテナ起動、イメージ作成

ルートディレクトリ(ここではリポジトリ名である adoption)に移動し、

```
docker-compose up -d
```

を powershell 等で実行

### frontend 起動方法

frontend コンテナのログを確認(Docker Desktop で log を見るか、または

```
docker container logs -f --tail=100 frontend
```

)で、無事にビルドが通れば

```
http://localhost:5173/
```

にアクセス
