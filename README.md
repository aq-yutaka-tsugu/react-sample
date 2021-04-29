# react-sample

### ■環境構築
下記スクリプト実行
```
docker-compose up --build -d
docker-compose run --rm app cp .env.example .env
docker-compose run --rm app composer install
docker-compose run --rm node install
docker-compose run --rm node run dev
```

下記にアクセス
* Docker
  http://localhost/

* Docker toolbox
  http://192.168.99.100/