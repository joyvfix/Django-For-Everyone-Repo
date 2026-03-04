# 📝 Quiz & Latihan — Modul 07: URL & Views

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

**Soal 1:** Apa fungsi file urls.py di Django?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Tuliskan contoh URL pattern untuk halaman 'tentang'!

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Apa yang wajib di-return oleh setiap view function?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Apa perbedaan render() dan HttpResponse()?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Bagaimana cara mengirim parameter melalui URL, misalnya ID artikel?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Apa fungsi file urls.py di Django?

> ✅ Mendefinisikan peta routing URL — URL mana diarahkan ke view mana.

---

**Jawaban Soal 2:** Tuliskan contoh URL pattern untuk halaman 'tentang'!

> ✅ path('tentang/', views.tentang, name='tentang')

---

**Jawaban Soal 3:** Apa yang wajib di-return oleh setiap view function?

> ✅ HttpResponse atau subclass-nya (JsonResponse, render, redirect, dll.)

---

**Jawaban Soal 4:** Apa perbedaan render() dan HttpResponse()?

> ✅ HttpResponse: mengembalikan teks/HTML mentah. render(): menggabungkan template dengan context dan mengembalikan HttpResponse.

---

**Jawaban Soal 5:** Bagaimana cara mengirim parameter melalui URL, misalnya ID artikel?

> ✅ path('artikel/<int:pk>/', views.detail_artikel, name='detail')

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
