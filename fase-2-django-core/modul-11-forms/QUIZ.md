# 📝 Quiz & Latihan — Modul 11: Forms & Validasi

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

**Soal 1:** Apa perbedaan Form dan ModelForm di Django?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Mengapa CSRF token penting?

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Bagaimana cara menampilkan error validasi di template?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Apa yang terjadi kalau form.is_valid() return False?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Apa yang perlu ditambahkan di tag form HTML untuk upload file?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Apa perbedaan Form dan ModelForm di Django?

> ✅ Form: form manual yang field-nya didefinisikan sendiri. ModelForm: form yang otomatis dibuat dari model — lebih efisien.

---

**Jawaban Soal 2:** Mengapa CSRF token penting?

> ✅ Mencegah serangan Cross-Site Request Forgery — request palsu dari website lain yang berpura-pura jadi user yang sudah login.

---

**Jawaban Soal 3:** Bagaimana cara menampilkan error validasi di template?

> ✅ {{ form.nama_field.errors }} untuk field tertentu, atau {{ form.errors }} untuk semua error.

---

**Jawaban Soal 4:** Apa yang terjadi kalau form.is_valid() return False?

> ✅ Form berisi error, data tidak valid. Re-render template dengan form yang berisi pesan error.

---

**Jawaban Soal 5:** Apa yang perlu ditambahkan di tag form HTML untuk upload file?

> ✅ enctype="multipart/form-data" harus ditambahkan ke tag <form>.

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
