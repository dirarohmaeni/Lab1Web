Nama: Dira Rohmaeni 



NIM: 312410465



Kelas: TI.24.A5



# HTML


- Sebuah bahasa markup yang digunakan untuk membuat sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser.



- HTML berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai dengan yang diinginkan.



- HTML saat ini merupakan standar Internet yang didefinisikan dan dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).



# 1. Lakukan perubahan pada kode sesuai keinginan, amati error ketika salah penulisan tag



kesalahan menulis tag (misalnya <tittle> bukan <title> atau <mrk> bukan <mark>), browser biasanya tidak error fatal (nggak berhenti menampilkan halaman), tapi hasilnya tidak sesuai harapan.



Contoh: <tittle> → browser abaikan, jadi judul halaman kosong.



<mrk> → browser tidak kenal, jadinya dianggap teks biasa.



<a href="...Halaman 2></a> → link rusak, tidak bisa diklik.


# 2. Perbedaan <p> dan <br>


<p>Ini paragraf pertama.</p>
<p>Ini paragraf kedua.</p>



Ini baris pertama <br>
Ini baris kedua <br/>


# 3. Perbedaan atribut title dan alt pada <img>


alt (alternative text) → muncul jika gambar gagal dimuat. Juga dibaca screen reader untuk aksesibilitas.



title → teks tambahan yang muncul sebagai tooltip saat kursor diarahkan ke gambar.


# 4. Width & Height pada gambar


Kalau hanya isi salah satunya (misalnya width saja) → browser akan otomatis menyesuaikan yang lain agar gambar tetap proporsional (tidak gepeng).

Kalau isi dua-duanya (width & height) → kalau angkanya tidak sesuai rasio asli gambar, gambar bisa jadi melebar atau memanjang tidak proporsional.


# 5. Atribut target pada link (<a>)


Atribut target menentukan di mana halaman tujuan dibuka:



target="_blank" → buka link di tab baru / jendela baru.



target="_self" → buka link di tab yang sama (default).



target="_top" → buka link di jendela paling atas, berguna kalau ada frame/iframe.



target="_parent" → buka link di halaman induk dari iframe (kalau ada).



