# SetUp_MitApp_To_FireBase_2


# 🔁 SetUp MIT App Inventor ke Firebase (Lanjutan)

Ini adalah lanjutan dari panduan menghubungkan MIT App Inventor ke Firebase. Di tahap ini, kita akan menampilkan **data dari Firebase ke aplikasi MIT App Inventor** menggunakan komponen Label.

---

## 📌 Langkah-langkah

1. **Pastikan kamu sudah mengikuti langkah sebelumnya** untuk menghubungkan Firebase dengan MIT App (memasukkan URL dan Token).
2. Masuk ke tab **Designer**, dan ambil komponen:
   - `Label` → digunakan untuk menampilkan data dari Firebase (misalnya data sensor).
3. Masuk ke tab **Blocks**, lalu susun block diagram seperti berikut:

---

## 🔧 Contoh Block Diagram

```

```

Block ini berarti setiap kali ada perubahan data di Firebase pada node yang dimonitor, nilai tersebut akan langsung ditampilkan pada Label di aplikasi.

---

## 💡 Tips

- Pastikan nama komponen `FirebaseDB` dan `Label` sama dengan yang kamu gunakan di tab Designer.
- Gunakan ProjectBucket untuk menentukan data mana yang akan dimonitor.
- Kamu bisa menambahkan lebih banyak Label untuk menampilkan banyak data sekaligus dari Firebase.

---

✅ Dibuat oleh [Indra-MIK](https://github.com/Indra-MIK)
