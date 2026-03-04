# 📝 Quiz & Latihan — Modul 14: Static & Media Files

> Test pemahamanmu! Coba jawab dulu sebelum lihat kunci jawaban.

---

## 📌 Petunjuk

1. Baca setiap soal dengan teliti
2. **Jawab sendiri dulu** — jangan langsung lihat jawaban!
3. Cek jawaban di bagian bawah
4. Untuk soal coding — jalankan dan test kodenya!

**Sistem Nilai:**
- 5 soal benar = ⭐⭐⭐ Excellent!
- 4 soal benar = ⭐⭐ Good!  
- 3 soal benar = ⭐ Keep Learning!
- < 3 soal = 📚 Baca ulang materinya dulu

---

## ❓ Soal

**Soal 1:** Apa perbedaan static files dan media files di Django?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Mengapa perlu menjalankan collectstatic sebelum deploy?

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Library Python apa yang diperlukan untuk menggunakan ImageField?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Setting apa yang menentukan URL prefix untuk file upload?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Apa itu WhiteNoise dan untuk apa digunakan?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Apa perbedaan static files dan media files di Django?

> ✅ Static files: file statis (CSS, JS, gambar aset) yang tidak berubah. Media files: file yang diupload oleh user.

---

**Jawaban Soal 2:** Mengapa perlu menjalankan collectstatic sebelum deploy?

> ✅ Mengumpulkan semua static files dari seluruh app ke satu folder STATIC_ROOT agar bisa di-serve oleh web server.

---

**Jawaban Soal 3:** Library Python apa yang diperlukan untuk menggunakan ImageField?

> ✅ Pillow: pip install Pillow

---

**Jawaban Soal 4:** Setting apa yang menentukan URL prefix untuk file upload?

> ✅ MEDIA_URL di settings.py

---

**Jawaban Soal 5:** Apa itu WhiteNoise dan untuk apa digunakan?

> ✅ Middleware yang memungkinkan Django serve static files sendiri secara efisien di production, tanpa perlu Nginx/Apache khusus.

---

</details>

---

## 🚀 Tantangan Ekstra

Sudah selesai quiz? Coba tantangan ini:

1. Buat variasi project modul ini dengan fitur tambahan
2. Jelaskan konsep modul ini kepada teman/anggota keluarga dengan kata-kata sendiri
3. Cari contoh penerapan konsep ini di aplikasi populer (WhatsApp, Instagram, Tokopedia)

---

_Bagian dari [Django for Everyone](../../README.md) oleh Ahmad Faqih_
