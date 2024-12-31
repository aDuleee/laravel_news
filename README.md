Portal Berita Menggunakan Jetstream, Livewire, Sanctum, and Tailwind.

1. `git clone https://github.com/aDuleee/laravel_news.git`
2. `cd laravel-news`
3. `composer install` (bisa juga dengan `composer update` )
4. `cp .env.example .env`
5. `php artisan key:generate`
6.  sesuaikan file `.env` dengan database
7. `php artisan migrate:fresh --seed`
8. `php artisan storage:link`
9. `npm install && npm run dev` (jika tidak bisa, jalan kan satu persatu)
10. `php artisan serve`
11. buka link berikut `localhost:8000/login` untuk login  
12. pilih satu `email` dari tabel `users` Passwordnya `password`(cukup tulis "password").