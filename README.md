<div align="center">

# ForCrush

Halaman pesan sederhana dengan pertanyaan dan pilihan jawaban, dirancang sebagai template ringan untuk menyampaikan perasaan kepada seseorang yang spesial.

[Live Demo](https://dzareldeveloper.github.io/ForCrush/) · [Report an Issue](https://github.com/DzarelDeveloper/ForCrush/issues)

</div>

## Tentang Proyek

**ForCrush** adalah website statis satu halaman yang menampilkan dua pertanyaan, sebuah ilustrasi, serta tombol **Yes** dan **No**. Proyek ini menggunakan HTML dan CSS murni sehingga dapat dibuka langsung melalui browser tanpa instalasi, backend, database, atau proses build.

Versi saat ini berfokus pada tampilan antarmuka. Struktur tombol sudah tersedia, tetapi perilaku interaktifnya belum diterapkan karena file `script.js` yang dipanggil oleh halaman belum tersedia di repositori.

## Fitur Saat Ini

- Tampilan pertanyaan dengan tema romantis
- Ilustrasi yang dimuat dari aset eksternal
- Tombol pilihan **Yes** dan **No**
- Layout terpusat dengan desain ringan
- Dapat dijalankan pada hosting statis
- Tidak membutuhkan framework atau package manager

## Teknologi

- **HTML5** — struktur pertanyaan, gambar, dan tombol
- **CSS3** — layout, warna, tipografi, dan styling tombol
- **GitHub Pages** — hosting website statis

## Struktur Proyek

```text
ForCrush/
├── index.html    # Struktur halaman dan konten
├── style.css     # Tampilan halaman
├── README.md     # Dokumentasi proyek
└── LICENSE       # MIT License
```

> `index.html` memanggil `script.js`, tetapi file tersebut belum tersedia pada versi proyek saat ini.

## Menjalankan Secara Lokal

Tidak diperlukan instalasi dependensi.

1. Clone repositori:

   ```bash
   git clone https://github.com/DzarelDeveloper/ForCrush.git
   ```

2. Masuk ke direktori proyek:

   ```bash
   cd ForCrush
   ```

3. Jalankan local server:

   ```bash
   python -m http.server 8000
   ```

4. Buka `http://localhost:8000` melalui browser.

## Kustomisasi

### Mengubah pertanyaan

Edit kedua elemen dengan class `question` di dalam `index.html`.

### Mengganti gambar

Ubah atribut `src` pada elemen gambar. Gunakan aset lokal jika ingin halaman tetap bekerja tanpa koneksi internet:

```html
<img class="img" src="assets/message.png" alt="Ilustrasi pesan">
```

### Mengubah tema

Sesuaikan warna utama `#e94d58`, latar, font, ukuran tombol, dan jarak antarelemen melalui `style.css`.

### Menambahkan interaksi

Buat file `script.js` untuk menentukan respons tombol **Yes** dan **No**, misalnya mengganti teks, menampilkan ilustrasi baru, atau mengarahkan pengguna ke halaman lanjutan.

## Keterbatasan Saat Ini

- Tombol belum memiliki aksi karena `script.js` tidak tersedia.
- Gambar dimuat dari repositori eksternal sehingga memerlukan koneksi internet.
- Posisi tombol menggunakan ukuran tetap dan mungkin perlu disesuaikan untuk layar yang sangat kecil.

## Demo

**[Buka ForCrush Live Demo](https://dzareldeveloper.github.io/ForCrush/)**

## Lisensi

Proyek ini didistribusikan di bawah [MIT License](LICENSE).

## Author

Dibuat oleh [DzarelDeveloper](https://github.com/DzarelDeveloper).
