# 🐛 Masalah & Solusi — Modul 12: Autentikasi — Login & Register

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

## ❌ Masalah 1: Login berhasil tapi redirect ke /accounts/profile/

**🔴 Gejala / Pesan Error:**
```
Default redirect Django
```

**🟡 Penyebab:**
Ini terjadi karena tambahkan login_redirect_url = '/' di settings.

**✅ Solusi:**
Tambahkan LOGIN_REDIRECT_URL = '/' di settings.py untuk redirect ke halaman yang diinginkan.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: @login_required redirect loop

**🔴 Gejala / Pesan Error:**
```
Konfigurasi URL login salah
```

**🟡 Penyebab:**
Ini terjadi karena login_url belum diset atau url login salah.

**✅ Solusi:**
LOGIN_URL belum diset atau URL login salah. Tambahkan LOGIN_URL = '/login/' di settings.py.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 3: Password terlalu umum / terlalu pendek

**🔴 Gejala / Pesan Error:**
```
Validator password Django
```

**🟡 Penyebab:**
Ini terjadi karena django punya password validator bawaan.

**✅ Solusi:**
Django punya password validator bawaan. Untuk development, bisa dinonaktifkan di AUTH_PASSWORD_VALIDATORS.

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
