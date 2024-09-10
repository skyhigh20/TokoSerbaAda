
A.Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial).

1.Pada pertama saya membuat folder bernamakan "TokoSerbaAda" dimana folder ini akan menjadi folder utama dalam pengerjaan tugas ini
2.lalu di dalam folder "TokoSerbaAda" saya membuat folder lagi bernama "Main" dimana main ini menjadi folder untuk Ini menjadi pusat konfigurasi seperti settings, urls, wsgi.
3.Buat folder dengan nama "Main" dalam folder "AplikasiToko". folder ini akan mengelola model, views, dan templates.
4.Di folder "Main", buat model Product dengan atribut name, price, dan description. Model ini untuk meyimpan produk
5.di folder main Buat fungsi untuk menampilkan data menggunakan template HTML yang menunjukkan nama aplikasi dan identitas pribadi. Fungsi ini bertujuan menampilkan data produk secara rapi dalam web.
6.Tambahkan URL routing di urls.py dari folder "Main" untuk menghubungkan URL dengan fungsi view yang dibuat.
7.Lalu membuat folder projek baru bernama "Aplikasi Toko" yang isinya berupa asgi.py: Konfigurasi ASGI untuk proyek, digunakan untuk deployment menggunakan ASGI servers. settings.py: Berisi konfigurasi dan setting proyek Django, seperti database, middleware, dan aplikasi terinstall juga host, urls.py: Mendefinisikan URL routes untuk proyek. Ini adalah pintu masuk untuk permintaan URL., dan wsgi.py: Digunakan untuk deployment WSGI, konfigurasi interaksi server web dengan Django.
8. selanjutnya env: Direktori environment virtual Python, menyimpan semua paket yang diperlukan untuk proyek.
9. lalu membuat file requierements.txt utnuk mendownload pip untuk membuat projek django lalu install pip requirements.txt
9. lalu menabahkan file .gitignore: File yang menentukan file atau direktori yang harus diabaikan oleh git.
10.selanjutnya Deploy aplikasi ke PWS (Python Web Server) agar dapat diakses publik melalui internet.
11. menambahkan file tambahan seperti procfile untuk mengetahui jalannya proyek lalu selesai tahapannya.

NOTES:
jelas masih ada error di bagian pwsnya, sebelumnya sudah mengikuti arahan dari masalah yang sama saya ngalamin di forum diskusi, tapi tetap aja hasilnya masih sama error di bagian pws ataupun tdk ada tampilan di link pwsnya. Karena itu mohon maaf ketidaksempurnaan dalam pengerjaan. Sekian Terima kasih


B.Buatlah bagan yang berisi request client ke web aplikasi berbasis Django beserta responnya dan jelaskan pada bagan tersebut kaitan antara urls.py, views.py, models.py, dan berkas html.



C. Jelaskan fungsi git dalam pengembangan perangkat lunak!

-Git memungkinkan user untuk menyimpan "snapshot" dari proyek mereka pada interval waktu tertentu. Hal ini memudahkan untuk mengembalikan perubahan atau membandingkan versi kode sebelumnya.
-Git memudahkan kolaborasi antar pengembang dalam proyek yang sama. Dengan Git, beberapa pengembang dapat bekerja pada fitur yang berbeda tanpa mengganggu pekerjaan orang lain.
-Setiap commit di Git menyimpan informasi tentang siapa yang membuat perubahan dan apa saja perubahannya, memudahkan audit dan pelacakan perubahan.
-Git mendukung pembuatan cabang yang memungkinkan eksperimen atau pengembangan fitur tanpa mempengaruhi basis kode utama.


D. Menurut Anda, dari semua framework yang ada, mengapa framework Django dijadikan permulaan pembelajaran pengembangan perangkat lunak?

Dokumentasi yang Lengkap dan Komunitas yang Besar, dengan hal itu memudahkan pemula untuk memulai dan mendapatkan dukungan.
Batteries Included, Django menyediakan banyak fitur standar yang dibutuhkan untuk aplikasi web modern, seperti autentikasi, template engine, dan ORM, yang mempercepat proses pembangunan aplikasi.
Konvensi Ketimbang Konfigurasi, Django mengikuti pola "konvensi ketimbang konfigurasi" yang mengurangi jumlah keputusan yang harus dibuat pengembang, mempercepat pembelajaran dan pengembangan.


E.Mengapa model pada Django disebut sebagai ORM?

ORM (Object-Relational Mapping) dalam konteks Django adalah komponen yang memungkinkan interaksi dengan database menggunakan Python class yang map ke tabel database. ORM memungkinkan dalam
menggunakan bahasa Python yang bersifat lebih alami untuk operasi basis data tanpa harus menulis SQL secara langsung. serta Menyediakan abstraksi yang membantu menjaga keamanan data dan mengintegrasikan fungsi database dengan lebih mudah dan aman seperti transaksi dan migrasi skema.



