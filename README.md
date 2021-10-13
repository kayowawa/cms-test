## BackEnd:Laravel + FrontEnd:Nuxt(typescript)の環境構築

### ENVは環境により適宜変更

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



## git clone...


### Laravel

```
$ docker-compose exec api composer install
$ php artisan migrate
```

### yarn

```
$ docker-compose exec web yarn install 
```
