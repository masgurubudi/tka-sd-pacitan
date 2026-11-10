# Try Out TKA SD/MI — Matematika

Aplikasi Try Out TKA Matematika untuk SD/MI se-Kabupaten Pacitan.
4 paket soal (satu per domain CP TKA Matematika), masing-masing 30 soal,
waktu 60 menit per paket.

- Halaman siswa: `index.html` — pilih paket, isi nama + kelas, pilih kecamatan,
  pilih sekolah, masukkan NPSN sekolah (gate), kerjakan 30 soal, nilai langsung tampil
  beserta rincian jawaban dan pembahasan.
- Halaman guru: `guru.html` — masuk dengan PIN (NPSN sekolah atau PIN master),
  Matriks Nilai per siswa (nilai terbaik per paket), saringan kecamatan, Export Excel.
- Nilai tersimpan otomatis ke Firestore, koleksi `tryout_tka_sd` (proyek
  `database-mpi-spendaka`).

Dibuat oleh MGMP Matematika Kabupaten Pacitan.
