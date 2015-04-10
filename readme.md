# LaravelBlog

## Installation

git clone https://github.com/joelwei/LaravelBlog.git projectname  
cd projectname  
composer install  
create a database and inform .env  
php artisan key:generate  
php artisan migrate to create tables  
php artisan db:seed to populate tables  

default user ['ganto@qq.com' => '123456']  

>redis or memcache cache is required.
