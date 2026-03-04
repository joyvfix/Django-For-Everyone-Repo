# 📝 Quiz & Latihan — Modul 08: Templates & HTML Django

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

**Soal 1:** Apa sintaks untuk menampilkan variabel 'nama' dalam template Django?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Bagaimana cara membuat loop for di template Django?

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Apa itu template inheritance dan mengapa berguna?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Apa perbedaan {% %} dan {{ }} di template Django?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Bagaimana cara mengirim data dari view ke template?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Apa sintaks untuk menampilkan variabel 'nama' dalam template Django?

> ✅ {{ nama }}

---

**Jawaban Soal 2:** Bagaimana cara membuat loop for di template Django?

> ✅ {% for item in items %} ... {% endfor %}

---

**Jawaban Soal 3:** Apa itu template inheritance dan mengapa berguna?

> ✅ Membuat template dasar (base.html) yang diwarisi template lain. Berguna agar tidak mengulang header/footer/navbar di setiap halaman.

---

**Jawaban Soal 4:** Apa perbedaan {% %} dan {{ }} di template Django?

> ✅ {% %}: untuk tag logika (if, for, extends, block). {{ }}: untuk menampilkan nilai variabel.

---

**Jawaban Soal 5:** Bagaimana cara mengirim data dari view ke template?

> ✅ Melalui context dictionary di render(): return render(request, 'template.html', {'key': value})

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
