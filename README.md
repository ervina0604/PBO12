

# 📚 Aplikasi CRUD Java Persistence API untuk Pengelolaan Data - Pertemuan Duabelas

**Topik Utama:** Aplikasi CRUD menggunakan JPA untuk mengelola data dalam database 📊

---

## 📑 Daftar Isi
- [🔗 Koneksi Database dengan JPA](https://github.com/ervina0604/PBO12/blob/main/META-INF/persistence.xml)
- [🛠️ Konfigurasi Persistence Unit](https://github.com/ervina0604/PBO12/blob/main/pbo12/Matakuliah.java)
- [🛠️ Implementasi CRUD](https://github.com/ervina0604/PBO12/blob/main/pbo12/GuiMataKuliah.java)

---


## 📋 Langkah-Langkah Penggunaan

### 1. Membuat Persistence Unit
Klik kanan pada package proyek, lalu pilih **New > Entity Classes from Database** untuk membuat persistence unit. Persistence unit ini mengelola komunikasi antara aplikasi dan database.
    ![image](https://github.com/user-attachments/assets/b8f8e140-1f2b-4013-be13-404f8212a0a4)

---

### 2. Pilih Koneksi Database
Pilih koneksi database yang sudah dikonfigurasi atau buat koneksi baru jika belum tersedia:
- Pastikan Anda sudah menambahkan koneksi database yang sesuai dengan database yang akan digunakan.
![image](https://github.com/user-attachments/assets/1f579336-e2dc-4a99-8b13-1e9cbc1c715f)

---

### 3. Pilih Tabel yang Dibutuhkan
Pilih tabel-tabel yang akan digunakan dalam aplikasi:
- Pindahkan tabel yang diinginkan dari kolom kiri ke kolom kanan untuk digunakan dalam persistence unit.
![image](https://github.com/user-attachments/assets/26978d35-44f9-48f3-b29e-6bcbb6df49b6)

---

### 4. Klik Next
Lanjutkan ke tahap berikutnya dengan menekan **Next** setelah memilih tabel.
![image](https://github.com/user-attachments/assets/2cb61565-2452-4abb-af9d-139304c4ee56)

---

### 5. Klik Finish
Tekan **Finish** untuk menyelesaikan konfigurasi. Persistence unit dan kelas entitas akan dibuat otomatis berdasarkan tabel yang dipilih.
![image](https://github.com/user-attachments/assets/7ae7a82c-4e7d-4ed1-9678-672096a17bbf)

![image](https://github.com/user-attachments/assets/215cbab0-62f6-4b5b-9362-ee23518449a8)

---

### 6. Tambahkan Kode untuk Setiap Operasi CRUD
Tambahkan kode untuk mendukung operasi CRUD di aplikasi:
- **Insert Data** – Menambahkan data baru ke dalam database.
  ![image](https://github.com/user-attachments/assets/16b59105-2869-40bd-8f1b-49b3aad22ec3)

- **Update Data** – Memperbarui data yang ada di dalam database.
  ![image](https://github.com/user-attachments/assets/0644d930-260e-400d-a7c4-88db7c45d8d2)

- **Delete Data** – Menghapus data dari database.
  ![image](https://github.com/user-attachments/assets/d867dc95-1cc4-4204-8646-fac616f491c2)

- **Tampilkan Data** – Menampilkan data ke tabel di antarmuka aplikasi.
  ![image](https://github.com/user-attachments/assets/1c9a80e3-0c11-4139-b5b0-3b2df95d2356)

---

### 7. Tambahkan Button Cetak dan Upload
Tambahkan tombol untuk fungsi tambahan:
- **Button Cetak**: Untuk mencetak data yang diambil dari database ke file (misalnya, dalam format CSV).
- ![image](https://github.com/user-attachments/assets/d29aa0d6-b9a7-4315-ae4e-9e9e026000b6)

- **Button Upload**: Untuk mengunggah data baru ke dalam database.
- ![image](https://github.com/user-attachments/assets/5df8ed67-e1f3-4e9e-97d8-f4e37a02f5cc)


---

### 🚀 Selamat Belajar dan Mengaplikasikan JPA untuk Pengembangan Aplikasi! 💻
