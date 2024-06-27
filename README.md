Sistem Infromasi Managemen dan Penyewaan Kost

Cara run:
1. Pertama kali clone : composer install 
2. Copy env
3. Setting env database sesuaikan namanya dengan yang ada di phpmyadmin, misalnya nama database = db_kosan
4. Buat database di phpmyadmin db_kosan
5. Jalankan php artisan migrate , untuk migrasi database 
6. Jalankan php artisan db:seed untuk migrasi isi database tertentu
7. Jalankan php artisan storage:link
8. Running project dengan jalankan php artisan serve

How to run:
1. First time clone: composer install 
2. Copy env
3. Set the database env adjust the name to the one in phpmyadmin, for example database name = db_kosan
4. Create a database in phpmyadmin db_kosan
5. Run php artisan migrate, for database migration 
6. Run php artisan db:seed for migration of specific database contents
7. Run php artisan storage:link
8. Run the project by running php artisan serve