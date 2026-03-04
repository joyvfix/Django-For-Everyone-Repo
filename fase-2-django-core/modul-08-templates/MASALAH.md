# 🐛 Masalah & Solusi — Modul 08: Templates & HTML Django

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

## ❌ Masalah 1: TemplateDoesNotExist

**🔴 Gejala / Pesan Error:**
```
Lokasi template salah
```

**🟡 Penyebab:**
Ini terjadi karena django tidak menemukan file template.

**✅ Solusi:**
Django tidak menemukan file template. Pastikan folder templates ada di dalam app, dan app terdaftar di INSTALLED_APPS.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 2: Variabel template tidak muncul

**🔴 Gejala / Pesan Error:**
```
Context tidak dikirim dari view
```

**🟡 Penyebab:**
Ini terjadi karena pastikan variabel dikirim via context di render().

**✅ Solusi:**
Pastikan variabel dikirim via context di render(). Cek ejaan nama variabel di template dan view sama persis.

**🛡️ Pencegahan:**
Biasakan untuk selalu cek konfigurasi sebelum menjalankan program. Baca pesan error dari baris pertama — biasanya sudah ada petunjuk solusinya.

---

## ❌ Masalah 3: {% extends %} harus di baris pertama

**🔴 Gejala / Pesan Error:**
```
Template inheritance error
```

**🟡 Penyebab:**
Ini terjadi karena tag extends harus menjadi tag pertama dalam template.

**✅ Solusi:**
Tag extends harus menjadi tag pertama dalam template. Tidak boleh ada konten apapun sebelumnya.

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
