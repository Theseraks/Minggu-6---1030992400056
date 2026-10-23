Soal 1: Apa itu JavaScript dan kegunaannya
JavaScript adalah bahasa pemrograman tingkat tinggi yang bersifat interpreted dan dijalankan terutama di browser (sisi klien), meskipun juga bisa berjalan di server lewat Node.js. Jika HTML berperan sebagai struktur halaman dan CSS sebagai tampilan, maka JavaScript berperan memberi perilaku dan interaksi pada halaman web.

Kegunaan utamanya:
1. Membuat halaman web yang interaktif (tombol, menu, slider, dan sebagainya)
2. Memanipulasi elemen HTML dan CSS secara dinamis lewat DOM
3. Validasi form di sisi klien sebelum data dikirim ke server
4. Menangani event seperti klik, input keyboard, dan hover
5. Mengambil data dari server tanpa memuat ulang halaman (AJAX/Fetch)
6. Membangun aplikasi web, game sederhana, bahkan aplikasi server dan mobile

Soal 2: Apa itu jQuery dan kegunaannya
jQuery adalah library JavaScript yang ringan dan banyak dipakai, dibuat untuk menyederhanakan penulisan kode JavaScript. Mottonya “write less, do more”. jQuery bukan bahasa baru, melainkan kumpulan fungsi siap pakai yang dibangun di atas JavaScript.

Kegunaan utamanya:
1. Memilih dan memanipulasi elemen HTML dengan sintaks singkat (misalnya $("#id"))
2. Menangani event dengan lebih sederhana (.click(), .hover(), dan sebagainya)
3. Membuat efek dan animasi (.hide(), .show(), .fadeIn(), .animate())
4. Mengubah gaya CSS dan isi elemen dengan mudah (.css(), .html(), .text())
5. Mempermudah AJAX
6. Menjaga kompatibilitas antar browser

## Soal 3: Perbedaan JavaScript dan jQuery

| Aspek | JavaScript | jQuery |
|---|---|---|
| Jenis | Bahasa pemrograman | Library (kumpulan fungsi) yang ditulis dengan JavaScript |
| Ketergantungan | Berdiri sendiri, dijalankan langsung oleh browser | Membutuhkan JavaScript dan harus dimuat dulu (misalnya lewat CDN) |
| Sintaks | Lebih panjang, misalnya `document.getElementById("kotak")` | Lebih ringkas, misalnya `$("#kotak")` |
| Cakupan | Luas: logika, struktur data, fungsi, objek, dan lainnya | Terbatas pada manipulasi DOM, event, efek, dan AJAX |
| Kemudahan | Butuh pemahaman lebih dalam | Lebih mudah untuk pemula pada tugas DOM |
| Ukuran dan performa | Tanpa beban tambahan, lebih cepat | Ada tambahan file yang harus dimuat sehingga sedikit lebih berat |
Contoh perbandingan untuk menyembunyikan elemen:

### Contoh perbandingan: menyembunyikan elemen

```js
// JavaScript
document.getElementById("kotak").style.display = "none";

// jQuery
$("#kotak").hide();
```
