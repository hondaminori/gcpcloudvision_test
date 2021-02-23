# README

GCP CloudVision API を使ってタグ付けをしてみました。
以下の手順で多分試せます

### 1. GCPでプロジェクト作成とAPIキー取得

### 2. 本リポジトリを適当な場所へclone

### 3. bundle install と rails db:migrate 実行

### 4. プロジェクト直下で touch .env 実行

### 5. .envにキーを書く

```
GOOGLE_API_KEY="取得したキー"
```

あとは rails s なり何なりと。