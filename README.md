# お問い合わせフォーム  

## 環境構築  

### Dockerビルド  
1. https://github.com/manami0630/fashionably-late.git 
2. `docker-compose up -d --build`  

> MySQLは、OSによって起動しない場合がありますので、それぞれのPCに合わせて `docker-compose.yml` ファイルを編集してください。  

### Laravel環境構築  
1. `docker-compose exec php bash`  
2. `composer install`  
3. `.env.example` ファイルから `.env` を作成し、環境変数を変更  
4. `php artisan key:generate`  
5. `php artisan migrate`  
6. `php artisan db:seed`  

## 使用技術  
- PHP 8.0  
- Laravel 10.0  
- MySQL 8.0

## ER図
![スクリーンショット 2025-04-03 202550](https://github.com/user-attachments/assets/12eb5ea0-a695-4fea-9a03-43305b68503a)


## URL  
- 開発環境： [http://localhost/](http://localhost/)  
- phpMyAdmin： [http://localhost:8080/](http://localhost:8080/)  
