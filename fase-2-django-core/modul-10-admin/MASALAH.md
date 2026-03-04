# 🐛 Masalah & Solusi — Modul 10: Django Admin Panel

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

## ❌ Masalah 1: Admin tidak menampilkan model

**🔴 Gejala / Pesan Error:**
```
Lupa register model
```

**🟡 Penyebab:**
Ini terjadi karena pastikan model sudah diregister di admin.

**✅ Solusi:**
Pastikan model sudah diregister di admin.py: admin.site.register(NamaModel).

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: Tidak bisa akses /admin/

**🔴 Gejala / Pesan Error:**
```
Belum buat superuser
```

**🟡 Penyebab:**
Ini terjadi karena pastikan sudah jalankan migrate dan buat superuser: python manage.

**✅ Solusi:**
Pastikan sudah jalankan migrate dan buat superuser: python manage.py createsuperuser.

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
