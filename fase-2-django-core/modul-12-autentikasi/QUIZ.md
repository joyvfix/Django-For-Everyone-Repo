# 📝 Quiz & Latihan — Modul 12: Autentikasi — Login & Register

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

**Soal 1:** Apa decorator yang digunakan untuk membatasi akses halaman hanya untuk user yang sudah login?

```
Jawabanmu: ___________________________
```

---

**Soal 2:** Apa perbedaan autentikasi dan otorisasi?

```
Jawabanmu: ___________________________
```

---

**Soal 3:** Mengapa sebaiknya membuat custom user model di awal proyek?

```
Jawabanmu: ___________________________
```

---

**Soal 4:** Setting apa yang menentukan redirect setelah login berhasil?

```
Jawabanmu: ___________________________
```

---

**Soal 5:** Bagaimana cara logout user di Django?

```
Jawabanmu: ___________________________
```

---


## 🔑 Kunci Jawaban

<details>
<summary>👆 Klik untuk lihat jawaban (coba sendiri dulu!)</summary>

**Jawaban Soal 1:** Apa decorator yang digunakan untuk membatasi akses halaman hanya untuk user yang sudah login?

> ✅ @login_required

---

**Jawaban Soal 2:** Apa perbedaan autentikasi dan otorisasi?

> ✅ Autentikasi: verifikasi identitas (siapa kamu?). Otorisasi: verifikasi hak akses (apa yang boleh kamu lakukan?).

---

**Jawaban Soal 3:** Mengapa sebaiknya membuat custom user model di awal proyek?

> ✅ Sangat sulit mengubah user model setelah ada data. Custom model memberikan fleksibilitas menambah field (foto, nomor telepon, dll).

---

**Jawaban Soal 4:** Setting apa yang menentukan redirect setelah login berhasil?

> ✅ LOGIN_REDIRECT_URL di settings.py. Default: '/accounts/profile/'

---

**Jawaban Soal 5:** Bagaimana cara logout user di Django?

> ✅ Gunakan LogoutView bawaan Django atau panggil auth.logout(request) di view.

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
