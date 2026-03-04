# 📝 Quiz & Latihan — Modul 09: Models & Database

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

**Soal 1:** Apa itu ORM dan apa keuntungannya?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Bagaimana cara mengambil semua object dari model Artikel?

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Apa perintah untuk membuat dan menjalankan migrasi?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Apa perbedaan ForeignKey dan ManyToManyField?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Bagaimana cara filter artikel dengan kategori 'teknologi'?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Apa itu ORM dan apa keuntungannya?

> ✅ Object-Relational Mapper — memungkinkan interaksi dengan database menggunakan Python tanpa menulis SQL. Lebih aman, lebih mudah, database-agnostic.

---

**Jawaban Soal 2:** Bagaimana cara mengambil semua object dari model Artikel?

> ✅ Artikel.objects.all()

---

**Jawaban Soal 3:** Apa perintah untuk membuat dan menjalankan migrasi?

> ✅ python manage.py makemigrations → python manage.py migrate

---

**Jawaban Soal 4:** Apa perbedaan ForeignKey dan ManyToManyField?

> ✅ ForeignKey: relasi many-to-one (banyak artikel, satu penulis). ManyToManyField: relasi many-to-many (artikel bisa punya banyak tag, tag bisa ada di banyak artikel).

---

**Jawaban Soal 5:** Bagaimana cara filter artikel dengan kategori 'teknologi'?

> ✅ Artikel.objects.filter(kategori='teknologi')

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
