# 🐛 Masalah & Solusi — Modul 13: Class-Based Views (CBV)

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

## ❌ Masalah 1: AttributeError: Generic detail view must be called with object pk or slug

**🔴 Gejala / Pesan Error:**
```
URL tidak sesuai untuk CBV
```

**🟡 Penyebab:**
Ini terjadi karena url harus menyertakan pk atau slug.

**✅ Solusi:**
URL harus menyertakan pk atau slug. Contoh: path('artikel/<int:pk>/', DetailView.as_view()).

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: ImproperlyConfigured: No URL to redirect to

**🔴 Gejala / Pesan Error:**
```
Lupa definisikan redirect setelah sukses
```

**🟡 Penyebab:**
Ini terjadi karena createview/updateview butuh success_url atau get_absolute_url() di model.

**✅ Solusi:**
CreateView/UpdateView butuh success_url atau get_absolute_url() di model.

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
