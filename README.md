## Nama : Shofi Aulianda
## NIM : 312510183
## Kelas : TI.25.A.2
## Pertemuan : 12

## Input Kode Praktikum 7

<img width="582" height="413" alt="Screenshot_20251204_090247" src="https://github.com/user-attachments/assets/43394224-9d59-448e-8b37-ab45c0c78df9" />

## Output Kode Praktikum 7

<img width="536" height="254" alt="Screenshot_20251204_090312" src="https://github.com/user-attachments/assets/3b7eaa24-8a15-4b06-8779-1f7b37406422" />

## FLOWCHART
```
          ┌──────────────┐
          │   MULAI      │
          └──────┬───────┘
                 ↓
        ┌──────────────────┐
        │ Tampilkan Menu   │
       └──────┬──────────┘
               ↓
     ┌───────────────────────┐
     │ Input pilihan (1-5)   │
     └──────────┬────────────┘
                ↓
 ┌──────────────┼──────────────────────────────┐
 │              │                              │
 ↓              ↓                              ↓
(1) Tambah   (2) Tampil                     (3) Hapus
 Data        Data                           Data
 │              │                              │
 └──────┬───────┘                              │
        ↓                                       ↓
   kembali ke menu                         kembali ke menu

        ┌───────────────┐
        │     (4) Ubah   │
        │       Data     │
        └────────┬───────┘
                 ↓
           kembali ke menu

                 ↓
        ┌──────────────────┐
        │   (5) Keluar     │
        └──────────────────┘
                 ↓
           ┌───────────┐
           │   SELESAI  │
           └───────────┘
```
## DIAGRAM CLASS (UML)
```
+-------------------------+
|  DaftarNilaiMahasiswa   |
+-------------------------+
| - data: dict            |
+-------------------------+
| + tambah(nama, nilai)   |
| + tampilkan()           |
| + hapus(nama)           |
| + ubah(nama, nilaiBaru) |
+-------------------------+
```
Keterangan:

data → dictionary penyimpanan (nama → nilai)

tambah() → menambah data

tampilkan() → menampilkan data

hapus() → menghapus data

ubah() → mengubah nilai mahasiswa

## Penjelasan README.md

## Praktikum 8 – Program Daftar Nilai Mahasiswa (OOP)

Program ini dibuat untuk memenuhi tugas Praktikum 8 dengan menerapkan konsep **Object-Oriented Programming (OOP)** dalam bahasa Python.  
Program menggunakan sebuah class bernama `NilaiMahasiswa` yang berfungsi untuk mengelola data nilai mahasiswa.

---

## Tujuan Program
- Mengaplikasikan pemrograman berbasis objek (OOP)
- Menggunakan class, atribut, dan method
- Melakukan operasi tambah, tampilkan, hapus, dan ubah data mahasiswa

---

## Fitur Program

### 1. `tambah(nama, nilai)`
Menambahkan data mahasiswa baru ke dalam dictionary.

### 2. `tampilkan()`
Menampilkan semua data mahasiswa.  
Jika belum ada data, akan muncul pesan: **"Belum ada data."**

### 3. `hapus(nama)`
Menghapus data berdasarkan nama mahasiswa.  
Jika nama tidak ditemukan, tampil pesan error.

### 4. `ubah(nama, nilai_baru)`
Mengubah nilai mahasiswa.  
Jika nama tidak ada dalam data, tampil pesan error.

---


---

## Penjelasan Program

Program ini menggunakan konsep dasar OOP:

### ✔ **Class**
`NilaiMahasiswa` digunakan untuk menyimpan dan mengelola data mahasiswa.

### ✔ **Atribut**
- `self.data` → dictionary yang menyimpan pasangan (nama: nilai)

### ✔ **Method**
- `tambah()` → memasukkan data baru
- `tampilkan()` → menampilkan seluruh data
- `hapus()` → menghapus data berdasarkan kunci
- `ubah()` → memperbarui nilai mahasiswa
