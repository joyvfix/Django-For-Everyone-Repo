# 🐛 Masalah & Solusi — Modul 14: Static & Media Files

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

## ❌ Masalah 1: Static files tidak muncul di production

**🔴 Gejala / Pesan Error:**
```
Lupa collectstatic
```

**🟡 Penyebab:**
Ini terjadi karena jalankan python manage.

**✅ Solusi:**
Jalankan python manage.py collectstatic. Pastikan STATIC_ROOT dikonfigurasi di settings.py.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: Gambar upload tidak tampil

**🔴 Gejala / Pesan Error:**
```
Konfigurasi media files salah
```

**🟡 Penyebab:**
Ini terjadi karena pastikan media_url dan media_root dikonfigurasi.

**✅ Solusi:**
Pastikan MEDIA_URL dan MEDIA_ROOT dikonfigurasi. Tambahkan URL media di urls.py untuk development.

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
