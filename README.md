### 0 DBのenvは各環境ごとにzzz


### 開発環境立ち上げ
```
$ docker-compose up -d
```

### 初回

### 1. プロジェクトの作成
```
$ docker-compose exec web yarn create nuxt-app ./
```

### 2. 監視
```
$ docker-compose exec web yarn dev
```

### 3. プロジェクトの作成
```
$ docker-compose exec api composer create-project "laravel/laravel=" .
```

