# StudiKasus-Modul-3-PPL

Lakukan clone proyek pada device kalian masing masing git clone

composer update

duplikatkan file .env.example lalu duplikasi file tersebut direname menjadi .env 

Sesuaikan variabel APP_URL di file .env dengan port server teman-teman (contoh: http://localhost:8000 atau http://127.0.0.1:8000)

Generate key dengan perintah php artisan key:generate

Lakukan penyesuaian database pada .env 
contoh: DB_CONNECTION=mysql DB_HOST=127.0.0.1 DB_PORT=7000 DB_DATABASE=dusklaravel DB_USERNAME=root DB_PASSWORD=

Migrate database dengan perintah php artisan migrate

composer require laravel/dusk --dev

php artisan dusk:install

Jalankan proyek laravel dengan perintah php artisan serve & npm run dev pada terminal/cmd yang berbeda
#   S H I N T Y A - 1 2 0 2 2 2 4 1 8 7 - M O D U L 3  
 