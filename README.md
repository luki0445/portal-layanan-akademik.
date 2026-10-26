# Portal Layanan Akademik — KampusKu

Proyek tugas Pertemuan 5: Responsive & Accessible Web Client.

## Fitur
- Struktur HTML semantik: `header`, `nav`, `main`, `section`, `article`, `form`, dan `footer`.
- Empat kartu layanan akademik dengan tautan ke formulir.
- Formulir dengan nama, NIM, email, jenis layanan, keperluan, label, dan validasi HTML.
- Desain mobile-first menggunakan CSS Grid dan Flexbox.
- Skip link, label yang terhubung, indikator fokus keyboard, dan status hasil demo.
- Layout untuk viewport 360 px, 768 px, dan 1280 px.

## Struktur folder
```text
portal_layanan_akademik/
├── index.html
├── css/
│   └── styles.css
├── evidence/
│   └── README.md
└── README.md
```

## Cara menjalankan
1. Ekstrak folder proyek.
2. Buka folder di Visual Studio Code.
3. Buka `index.html` di browser, atau jalankan dengan ekstensi Live Server.
4. Uji tampilan di lebar 360 px, 768 px, dan 1280 px menggunakan Chrome DevTools.

## Catatan penting
Formulir ini merupakan demonstrasi front-end. Validasi HTML dan pesan demo berjalan di browser, tetapi data belum disimpan atau dikirim ke server kampus. Untuk tugas ini, jangan masukkan data pribadi yang sebenarnya.

## Checklist pengujian DevTools
- [ ] Elements: pastikan struktur semantik dan heading berurutan.
- [ ] Responsive Mode: uji 360 px, 768 px, 1280 px; pastikan tidak ada scroll horizontal.
- [ ] Network: reload halaman, periksa apakah `index.html` dan `css/styles.css` berhasil dimuat.
- [ ] Keyboard: tekan Tab, pastikan tautan, input, select, textarea, dan tombol dapat dicapai serta fokus terlihat.
- [ ] Form: coba kirim dalam keadaan kosong; browser seharusnya menampilkan validasi. Uji email tidak valid.
- [ ] Accessibility/Inspector: periksa nama kontrol, label, heading, dan kontras.
- [ ] Simpan screenshot hasil pengujian di folder `evidence/`.

## Cara publikasi
- GitHub Pages: unggah isi folder ini ke repository GitHub, lalu buka Settings → Pages dan pilih branch utama serta folder root.
- Setelah publikasi, salin URL GitHub Pages ke laporan tugas.
