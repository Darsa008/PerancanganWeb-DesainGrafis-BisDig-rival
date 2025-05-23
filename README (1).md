# PerancanganWeb-DesainGrafis-BisDig

## Studi Kasus: Responsive Design untuk Situs Portofolio Mahasiswa

### Permasalahan:
Saat situs dibuka di smartphone, gambar terlihat terlalu besar dan teks meluber ke luar layar.

### Solusi:
Menggunakan pendekatan **responsive design** dalam CSS agar tampilan menyesuaikan ukuran layar perangkat. Teknik ini membantu membuat tampilan tetap rapi baik di HP, tablet, maupun desktop.

### Penjelasan Konsep:
- **Responsive Design** adalah pendekatan desain web agar tampilan menyesuaikan perangkat pengguna.
- **Media queries** digunakan untuk menetapkan aturan khusus sesuai lebar layar.

### Contoh CSS yang digunakan:
```css
img {
  max-width: 100%;
  height: auto;
}

@media screen and (max-width: 600px) {
  .container {
    width: 95%;
    font-size: 16px;
    padding: 10px;
  }
}
```

### File:
- `style.css` berisi kode lengkap untuk membuat gambar fleksibel dan layout responsif.