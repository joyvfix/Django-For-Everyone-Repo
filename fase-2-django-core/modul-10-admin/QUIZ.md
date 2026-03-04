# 📝 Quiz & Latihan — Modul 10: Django Admin Panel

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

**Soal 1:** Bagaimana cara mendaftarkan model ke Django Admin?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Apa perintah untuk membuat superuser?

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Apa kegunaan list_display di ModelAdmin?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Di URL mana Django Admin bisa diakses?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Apa itu inline admin dan kapan digunakan?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Bagaimana cara mendaftarkan model ke Django Admin?

> ✅ Di admin.py: from .models import Artikel
admin.site.register(Artikel)

---

**Jawaban Soal 2:** Apa perintah untuk membuat superuser?

> ✅ python manage.py createsuperuser

---

**Jawaban Soal 3:** Apa kegunaan list_display di ModelAdmin?

> ✅ Menentukan kolom apa yang ditampilkan di halaman daftar object di admin panel.

---

**Jawaban Soal 4:** Di URL mana Django Admin bisa diakses?

> ✅ http://127.0.0.1:8000/admin/

---

**Jawaban Soal 5:** Apa itu inline admin dan kapan digunakan?

> ✅ Menampilkan dan mengelola related model di dalam halaman model induk. Berguna misal edit artikel sekaligus komentar-komentarnya.

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
