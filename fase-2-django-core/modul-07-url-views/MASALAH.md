# 🐛 Masalah & Solusi — Modul 07: URL & Views

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

## ❌ Masalah 1: NoReverseMatch: Reverse for 'nama' not found

**🔴 Gejala / Pesan Error:**
```
Nama URL tidak sesuai
```

**🟡 Penyebab:**
Ini terjadi karena nama url di urls.

**✅ Solusi:**
Nama URL di urls.py dan template tidak cocok. Cek parameter name= di path() dan {% url 'nama' %}.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: 404 Page Not Found

**🔴 Gejala / Pesan Error:**
```
URL belum didaftarkan
```

**🟡 Penyebab:**
Ini terjadi karena url yang diakses tidak ada di urls.

**✅ Solusi:**
URL yang diakses tidak ada di urls.py. Cek apakah URL sudah didaftarkan dan app sudah di-include.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 3: View harus return HttpResponse

**🔴 Gejala / Pesan Error:**
```
Lupa return di view function
```

**🟡 Penyebab:**
Ini terjadi karena setiap view function wajib return response.

**✅ Solusi:**
Setiap view function wajib return response. Lupa return render() atau HttpResponse() akan menyebabkan error.

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
