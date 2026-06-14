# Penugasan Frontend Gerex - Kartu Profil Maba

## Deskripsi
Repositori ini berisi implementasi komponen "Kartu Profil Maba" untuk memenuhi Penugasan A (Frontend) pendaftaran Gerex. Komponen ini menampilkan Foto, Nama, NRP, dan Gugus.

## Pendekatan Pengerjaan
Dalam mengimplementasikan Kartu Profil Maba ini, saya memilih menggunakan **HTML dan CSS Murni (Vanilla)** dengan pendekatan *Separation of Concerns*. Struktur kerangka dibuat di HTML, sementara gaya visual dan layout diisolasi sepenuhnya di file `style.css` terpisah. 

Beberapa poin teknis dalam pendekatan saya:
1. **Tata Letak (Layouting):** Menggunakan **Flexbox** pada `body` untuk memusatkan kartu profil tepat di tengah layar (*viewport*).
2. **Proporsi Data:** Menggunakan **CSS Grid** pada bagian detail informasi (NRP & Gugus) agar mendapatkan lebar yang presisi dan sejajar.
3. **Responsivitas (Mobile-Friendly):** Menerapkan *Media Queries* `@media (max-width: 480px)`. Ketika diakses melalui perangkat *mobile*, layout grid NRP dan Gugus yang awalnya menyamping (2 kolom) akan otomatis berubah menjadi bersusun ke bawah (1 kolom) agar tampilan tetap rapi dan tidak saling bertumpuk.
4. **Desain Visual:** Menggunakan efek bayangan (*box-shadow*), transisi *hover* (*smooth transition*), serta trik margin negatif untuk membuat posisi avatar seolah menembus batas *banner*.

## Cara Menjalankan
1. *Clone* atau *download* repositori ini.
2. Pastikan file `index.html`, `style.css`, dan `foto.jpeg` berada di dalam satu folder yang sama.
3. Buka file `index.html` menggunakan *web browser* pilihan Anda.
