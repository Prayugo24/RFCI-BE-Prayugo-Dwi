# RFCI-BE--Prayugo-Dwi-

Untuk Menjalankan Client server app

1. Buka crontab -e
2. lalu seting cron seperti berikut
    - */1 * * * * php /var/www/html/Client-Server-App/artisan schedule:run >> /tmp/server.log
3. untuk folder projek disesuakan dengan cron agara bisa jalan
4. lalu save