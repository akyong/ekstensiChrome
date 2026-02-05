# Justice.gov PDF Navigator – Chrome Extension

Extension ini dibuat untuk **mempermudah membuka dan menavigasi file PDF DOJ (Epstein Disclosures)** yang jumlahnya sangat banyak, dengan sistem **Next / Back** dan **shortcut keyboard (← →)**.

Extension **TIDAK mem-bypass sistem website**, hanya membantu navigasi file PDF setelah user mengakses website secara resmi.

---

## ⚠️ Langkah WAJIB PERTAMA (Penting!)

Sebelum menggunakan extension, kamu **HARUS membuka website DOJ secara manual terlebih dahulu**.

### 1️⃣ Buka link berikut di browser https://www.justice.gov/epstein/doj-disclosures

Website pemerintah ini akan menampilkan pertanyaan:
> **Apakah kamu berusia 18 tahun atau lebih?**

👉 **Jawab secara manual di browser.**

Ini penting karena website menggunakan **cookie** untuk menandai bahwa kamu sudah menyetujui peringatan usia.  
Extension **tidak bisa dan tidak mencoba melewati langkah ini**.

---

### 2️⃣ Setelah itu, buka SATU file PDF terlebih dahulu
Contoh: https://www.justice.gov/epstein/files/DataSet%201/EFTA00000001.pdf

Jika file sudah bisa terbuka normal di browser, berarti akses sudah siap.

---

## 📁 Struktur Folder & File DOJ

Semua file PDF berada di struktur URL seperti ini:
https://www.justice.gov/epstein/files/{DATASET_FOLDER}/{FILENAME}.pdf


Contoh nyata:
https://www.justice.gov/epstein/files/DataSet%201/EFTA00000001.pdf


Artinya:
- `DataSet%201` → **nama folder dataset**
- `EFTA00000001.pdf` → **nama file PDF**

---

## 🧩 Cara Menggunakan Extension

Di extension yang kamu install, tersedia:
- **Kolom Dataset / Folder**
- **Kolom Index (nomor file)**
- Tombol **Prev / Next**
- Shortcut keyboard **← →**

---

### 3️⃣ Mengatur Dataset

Di halaman DOJ Disclosures, kamu akan melihat:
- DataSet 1
- DataSet 2
- DataSet 3
- dan seterusnya

Jika kamu ingin membuka **Dataset 1**, isi: DataSet%201 
Jika ingin **Dataset 2**, isi: DataSet%202

⚠️ Perhatikan: **harus pakai format URL encoding** (`%20` jadi `%` + `20` → `%201`, `%202`, dll)

---

## 🔢 Penting: Start Index Setiap Dataset

❗ **Tidak semua dataset dimulai dari EFTA00000001.pdf**

### Contoh: DataSet 2
- Folder: DataSet%202
- File pertama di dataset ini adalah: EFTA00003159.pdf

Artinya:
- Dataset 2 **dimulai dari index 3159**, bukan 1.

---

### 4️⃣ Cara Input yang Benar (Contoh DataSet 2)

1. Isi **Dataset / Folder**: DataSet%202
2. Isi **Index / Start**: 3159
3. Tekan **Next** → akan membuka: EFTA00003160.pdf
4. Tekan **Prev** → akan kembali ke: EFTA00003158.pdf

Extension akan melanjutkan penomoran **secara otomatis**.

---

## ⌨️ Shortcut Keyboard

Extension mendukung shortcut:
- **→ (Right Arrow)** → Next PDF
- **← (Left Arrow)** → Previous PDF

Shortcut bisa diubah lewat: chrome://extensions/shortcuts


Cari extension **Justice PDF Navigator**, lalu atur shortcut sesuai keinginan.

---

## 📌 Ringkasan Cepat

1. **Buka DOJ website dulu secara manual**
2. Jawab pertanyaan usia 18+
3. Buka satu PDF sampai berhasil
4. Atur:
   - Dataset folder (`DataSet%201`, `DataSet%202`, dst)
   - Start index sesuai file pertama dataset
5. Navigasi pakai:
   - Tombol Prev / Next
   - Keyboard ← →

---

## ✅ Tujuan Extension

- Tidak bypass sistem DOJ
- Tidak memodifikasi cookie secara ilegal
- Hanya **mempermudah navigasi PDF**
- Tetap mengandalkan akses resmi via browser

---

Jika dataset baru ditambahkan DOJ, cukup:
- Cek folder & file awalnya
- Update dataset + start index
- Lanjutkan navigasi 🚀


