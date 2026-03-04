# 🐛 Masalah & Solusi — Modul 11: Forms & Validasi

> Kumpulan error paling umum yang dialami peserta di modul ini, lengkap dengan solusi dan penjelasan mengapa terjadi.

---

## 💡 Cara Membaca Dokumen Ini

Setiap masalah dijelaskan dalam format:
- **Masalah**: Deskripsi error yang terjadi
- **Gejala**: Apa yang terlihat / pesan error
- **Penyebab**: Kenapa ini terjadi
- **Solusi**: Langkah-langkah mengatasi
- **Pencegahan**: Cara agar tidak terjadi lagi

---

## ❌ Masalah 1: Form valid tapi data tidak tersimpan

**🔴 Gejala / Pesan Error:**
```
Lupa panggil form.save()
```

**🟡 Penyebab:**
Ini terjadi karena panggil form.

**✅ Solusi:**
Panggil form.save() setelah if form.is_valid():. Untuk ModelForm, save() otomatis simpan ke database.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: CSRF token missing or incorrect

**🔴 Gejala / Pesan Error:**
```
Lupa CSRF token di template
```

**🟡 Penyebab:**
Ini terjadi karena tambahkan {% csrf_token %} di dalam tag <form>.

**✅ Solusi:**
Tambahkan {% csrf_token %} di dalam tag <form>. Wajib untuk semua form POST.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 3: File upload tidak berfungsi

**🔴 Gejala / Pesan Error:**
```
Form tidak dikonfigurasi untuk upload
```

**🟡 Penyebab:**
Ini terjadi karena tambahkan enctype="multipart/form-data" di tag <form> dan handle request.

**✅ Solusi:**
Tambahkan enctype="multipart/form-data" di tag <form> dan handle request.FILES di view.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## 🆘 Masalah Tidak Ada di Daftar?

1. **Copy pesan error lengkap** → Google → Stack Overflow
2. **Cek Django documentation** → docs.djangoproject.com
3. **Buka Discussion** di repo ini → [Diskusi](../../discussions)
4. **Tanya di komunitas** dengan menyertakan:
   - Pesan error lengkap
   - Kode yang bermasalah
   - Langkah yang sudah dicoba

---

_Temukan solusi baru? Kontribusikan ke repo ini! Lihat [CONTRIBUTING.md](../../CONTRIBUTING.md)_
