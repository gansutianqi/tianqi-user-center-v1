## usage

+ clone this repository
+ run `composer update`
+ make the `storage` and `bootstrap/cache` directory writable,and run below commander in you project root 
    * run `chmod -R 777 storage bootstrap/cache`
+ copy `.env.example` to `.env` with `cp .env.example .env`, and give you own settings
+ run `php artisan key:generate` generate a app key
+ run `php artisan storage:link` this make your upload assets access public
+ run `php artisan migrate` or `php artisan migrate:refresh`
+ laravel-passport
    * run `php artisan passport:install` for ready to use laravel-passport Personal Access Tokens
+ if there is any problems when run `npm install`, try use `npm install --no-bin-links`.




#### email
If use email , and add this to your `.env` file

```
MAIL_DRIVER=smtp
MAIL_HOST=smtp.qq.com
MAIL_PORT=465
MAIL_USERNAME=3190136675@qq.com
MAIL_PASSWORD=adxwvgbqhwejdfcj
MAIL_ENCRYPTION=ssl
MAIL_FROM_ADDRESS=3190136675@qq.com
MAIL_FROM_NAME=GanSuTianQi
``` 

