# AISIN
Membuat Project LARAVEL + VUE.JS

Object Aplikasi yang dibangun pada project ini ada 3 hal
- Membangun Sistem Register dan Login
- Melacak Koordinasi dan menampilkan di peta
- Menampilkan lampu berdasarkan parameter lampu yang diinginkan

Spesifikasi Aplikasi,
- LARAVEL PASSPORT AS BACKEND API
- VUE JS AXIOS AS FRONT END
- MySQL
- Server Local

**HOW TO SETUP THIS APP**
**1. Database**
- Open MySQL
- Make new database names " my_laravel_passport "
- run on cmd " Php artisan migrate " 
- run on cmd "php artisan passport:install "
- Done

**2. Setup laravel**
- run on cmd "php artisan serve "

**3. Setup Vue**
- run on cmd "npm install" 
- run on cmd "npm run serve" 

Report Aplikasi yang dibangun.
- Sukses Execute Register Login
- Sukses menampilkan titik koordinat lokasi
- Masih gagal dalam melakukan update warna lampu dengan connection database

REPORT BUG :
- Lokasi koordinat akan dicari berdasarkan asal mula koneksi internet, lokasi mungkin saja meleset jauh dari titik lokasi yang di harapkan bila menggunakan ISP atau Wifi Public/Kantor, untuk mengatasinya lakukan peritah "run npm serve" dengan uji coba menggunakan hotspot ponsel dan buka browser yang ada, kemudian cobalah kembali lacak.
- Bug tidak bisa update terkendala kehabisan waktu pengerjaan sehingga masih stuck dalam pembuatan API controller update untuk  request **put** kedalam server dengan database lampu

Penutup:
Mohon maaf bila masih banyak kekurangan dalam program, saya telah jujur mengerjakan semaksimal mungkin dengan waktu yang sangat minim perharinya.
mudah-mudahan lebih kurangnya dapat diterima. Terimakasih

Best. Regard
Rafie.
