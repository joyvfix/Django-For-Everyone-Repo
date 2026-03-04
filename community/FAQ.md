# ❓ FAQ — Pertanyaan yang Sering Ditanyakan

> Sebelum buka issue baru, cek dulu di sini — mungkin pertanyaanmu sudah ada jawabannya!

---

## 🟢 Umum

**Q: Apakah kursus ini cocok untuk yang belum pernah coding sama sekali?**
> A: Ya! Kursus ini dirancang dari nol. Modul 1–5 mengajarkan Python dari dasar sebelum masuk ke Django.

**Q: Berapa lama waktu yang dibutuhkan untuk menyelesaikan semua modul?**
> A: Tergantung intensitas belajar. Dengan belajar 2 jam/hari: sekitar 2–3 bulan. Santai 1 jam/hari: 4–6 bulan. Tidak ada batas waktu — belajar sesuai kemampuanmu.

**Q: Apakah ada biaya untuk mengakses repo ini?**
> A: Tidak! Semua materi di repo ini gratis. Repo ini adalah pendamping kursus utama.

**Q: Bahasa apa yang digunakan?**
> A: Bahasa Indonesia sebagai bahasa utama. Istilah teknis menggunakan bahasa Inggris (standar industri).

---

## 🐍 Python

**Q: Versi Python mana yang direkomendasikan?**
> A: Python 3.11 atau yang lebih baru. Cek: `python --version`

**Q: Haruskah saya menguasai Python dulu sebelum belajar Django?**
> A: Ya! Fase 1 (Modul 1–5) wajib diselesaikan dulu. Django tanpa fondasi Python yang kuat akan sangat sulit.

**Q: Apakah perlu belajar HTML/CSS sebelum Django?**
> A: Dasar HTML/CSS cukup (ada di Modul 5). Tidak perlu jadi ahli frontend — Django untuk backend.

---

## 🚀 Django

**Q: Django versi berapa yang digunakan?**
> A: Django 5.x (versi terbaru). Konsep utamanya sama untuk Django 3.x ke atas.

**Q: Apakah perlu beli hosting untuk belajar?**
> A: Tidak untuk belajar. Development cukup di komputer lokal. Modul 18 mengajarkan deploy ke platform gratis (Railway/Render).

**Q: Apa perbedaan Django dan Django REST Framework?**
> A: Django untuk membangun website tradisional (template + HTML). DRF untuk membangun API yang bisa diakses mobile app, React, dll.

---

## 🐛 Masalah Teknis

**Q: Perintah python tidak ditemukan di terminal!**
> A: Windows: pastikan centang "Add Python to PATH" saat install. Atau coba `python3`. Mac/Linux: gunakan `python3`.

**Q: Error "No module named django"**
> A: Virtual environment belum diaktifkan! Jalankan:
> ```bash
> source venv/bin/activate    # Mac/Linux
> venv\Scripts\activate       # Windows
> pip install django
> ```

**Q: Port 8000 sudah dipakai**
> A: Gunakan port lain: `python manage.py runserver 8080`

**Q: Bagaimana cara reset database dari awal?**
> A: Hapus file `db.sqlite3` dan semua file di folder `migrations/` (kecuali `__init__.py`). Lalu jalankan `makemigrations` dan `migrate` lagi.

---

## 📚 Belajar

**Q: Apakah boleh skip modul?**
> A: Tidak disarankan — setiap modul membangun di atas modul sebelumnya. Tapi kalau sudah familiar topiknya, bisa baca cepat dan fokus di bagian yang baru.

**Q: Bagaimana kalau stuck di satu topik?**
> A: Normal! Coba urutan ini: (1) Baca ulang materinya, (2) Google pesan error, (3) Cek MASALAH.md modul, (4) Buka Discussion di repo ini.

**Q: Apakah ada sertifikat setelah selesai?**
> A: Ya! Sertifikat tersedia melalui program kursus resmi Ahmad Faqih setelah menyelesaikan ujian akhir di Modul 24.

---

_Pertanyaanmu tidak ada di sini? Buka [Discussion](../discussions) atau [Issue](../issues/new)!_
