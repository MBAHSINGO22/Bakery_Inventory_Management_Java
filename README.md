
# 🍞 Bakery Inventory Management Java

## 📖 Deskripsi Proyek
Proyek pembelajaran Java yang mendemonstrasikan penggunaan **komposisi** dalam pemrograman berorientasi objek (OOP) untuk mengelola sistem inventaris toko roti.  
Program ini memungkinkan pengguna untuk mengelola data item, pegawai (manajer), dan toko, serta menyediakan fitur pencarian item termurah dan item yang habis stok.

---

## 🧠 Fitur Utama
- 📦 Pengelolaan data item (kode, nama, harga, stok)
- 🏢 Pengelolaan data toko (kode, nama)
- 👨‍💼 Pengelolaan data pegawai (manajer toko)
- 🔎 Fitur pencarian item termurah
- ⚠️ Fitur pencarian item habis stok
- 📊 Tampilan laporan inventaris lengkap

---

## 📂 Struktur Proyek
```
Bakery_Inventory_Management_Java/
├── src/UTS/
├── KelolaToko.java         # 🛠️ Kelas utama untuk menjalankan program
├── Item.java               # 📦 Kelas representasi item
├── Pegawai.java            # 👨‍💼 Kelas representasi pegawai/manajer
├── Toko.java               # 🏪 Kelas utama pengelola toko dan item
```

---

## 🧠 Catatan
- Program menerima input data toko, pegawai, dan item melalui **konsol**.
- Komposisi diterapkan pada relasi antara `Toko` dan `Pegawai`, serta antara `Toko` dan daftar `Item`.
- ArrayList digunakan untuk menyimpan daftar item.
- Fitur tambahan:
  - **Item termurah**: Menampilkan item dengan harga terendah.
  - **Item habis stok**: Menampilkan daftar item dengan stok = 0.

---

## 📈 Contoh Output
```
INPUT DATA TOKO ROTI & KUE
Masukkan jumlah item: 3

Masukkan data item 1:
Kode item: 001
Nama item: TAHU
Harga: 2000
Stok: 5

Masukkan data item 2:
Kode item: 002
Nama item: TEMPE
Harga: 3000
Stok: 10

Masukkan data item 3:
Kode item: DADA AYAM
Nama item: 003
Harga: 45000
Stok: 0

INPUT DATA TOKO
Kode Toko: 2205
Nama Toko: MBAH SINGO

INPUT DATA MANAJER
Kode Pegawai: 001
Nama: VANYA
Alamat: MINGGIR

INFORMASI TOKO ROTI & KUE
MBAH SINGO(2205)
Manajer: VANYA

Daftar Item:
Kode Item   Nama Item       Harga   Stok
-------------------------------------------
001        TAHU            2000.00    5
002        TEMPE           3000.00    10
DADA AYAM  003             45000.00   0

Item paling murah: TAHU, harga 2000.0, jumlah stok 5

Daftar item yang habis stoknya adalah:
Kode Item   Nama Item
--------------------------
DADA AYAM  003
```

---

## 👨‍💻 Pengembang
**MBAHSINGO22**  
🔗 GitHub: [https://github.com/MBAHSINGO22](https://github.com/MBAHSINGO22)
