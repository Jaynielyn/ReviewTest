お問い合わせフォーム

環境構築
Dockerビルド
git clone: git@github.com:coachtech-material/laravel-docker-template.git
docker-compose up -d --build

Laravel環境構築
1.docker-compose exec php bash
2.composer install
3..env.exampleファイルから.envを作成し、環境変数を変更
4.php artisan key:generate
5.php artisan migrate

使用技術
PHP 8.0
Laravel 10.0
Mysql 8.0

URL
環境開発: http://localhost/
phpMyAdmin: http://localhost:8080/
