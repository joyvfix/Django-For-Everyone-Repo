# 🐛 Masalah & Solusi — Modul 06: Django — Instalasi & Proyek Pertama

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

## ❌ Masalah 1: django.core.exceptions.ImproperlyConfigured

**🔴 Gejala / Pesan Error:**
```
Konfigurasi dasar Django salah
```

**🟡 Penyebab:**
Ini terjadi karena settings.

**✅ Solusi:**
settings.py belum dikonfigurasi dengan benar. Cek INSTALLED_APPS, DATABASES, dan SECRET_KEY.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: Port 8000 sudah dipakai

**🔴 Gejala / Pesan Error:**
```
Address already in use
```

**🟡 Penyebab:**
Ini terjadi karena jalankan di port lain: python manage.

**✅ Solusi:**
Jalankan di port lain: python manage.py runserver 8080. Atau hentikan proses lain yang pakai port 8000.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 3: ModuleNotFoundError: No module named 'django'

**🔴 Gejala / Pesan Error:**
```
Install Django di luar venv
```

**🟡 Penyebab:**
Ini terjadi karena virtual environment belum diaktifkan atau django belum diinstall.

**✅ Solusi:**
Virtual environment belum diaktifkan atau Django belum diinstall. Aktifkan venv dulu, lalu pip install django.

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
