# 🐛 Masalah & Solusi — Modul 09: Models & Database

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

## ❌ Masalah 1: django.db.utils.OperationalError: no such table

**🔴 Gejala / Pesan Error:**
```
Lupa migrasi setelah buat model
```

**🟡 Penyebab:**
Ini terjadi karena belum menjalankan migrasi.

**✅ Solusi:**
Belum menjalankan migrasi. Jalankan: python manage.py makemigrations && python manage.py migrate.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: ValueError: Field cannot be null

**🔴 Gejala / Pesan Error:**
```
Field null pada model
```

**🟡 Penyebab:**
Ini terjadi karena field yang required tidak boleh kosong.

**✅ Solusi:**
Field yang required tidak boleh kosong. Tambahkan null=True, blank=True atau berikan default value.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 3: Migrasi konflik

**🔴 Gejala / Pesan Error:**
```
Bekerja di branch berbeda dengan perubahan model
```

**🟡 Penyebab:**
Ini terjadi karena hapus file migrasi yang konflik (kecuali __init__.

**✅ Solusi:**
Hapus file migrasi yang konflik (kecuali __init__.py), jalankan makemigrations lagi. Atau gunakan --merge.

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
