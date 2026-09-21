# Bab 11 — for dan range()

**Tingkat:** Pemula  
**Tujuan:** Melakukan perulangan terkontrol dan memahami range dengan benar.

## 1. Penjelasan
for mengiterasi item dari iterable. range(stop) dimulai dari 0 dan berhenti sebelum stop.

## 2. Arti dan kegunaan
**Apa artinya?**  
for dan range() adalah bagian dari ekosistem Python yang membantu programmer menyelesaikan masalah tertentu dengan cara yang terstruktur.

**Mengapa dipakai?**  
Konsep ini membantu membuat program lebih mudah dibaca, diuji, dikembangkan, dan dipelihara. Penggunaannya harus disesuaikan dengan kebutuhan; tidak semua fitur perlu dipakai pada setiap program.

## 3. Cara mulai
Contoh latihan dasar:

```python
for i in range(5):
    print(i)
for nama in ['A', 'B']:
    print(nama)
```

Jalankan dari terminal:

```bash
python nama_file.py
```

Jika sistem menggunakan launcher `python3`, gunakan:

```bash
python3 nama_file.py
```

## 4. Hal penting yang harus dipahami
- Jangan hanya menghafal sintaks; pahami objek dan alur eksekusinya.
- Uji contoh kecil sebelum memasukkannya ke proyek besar.
- Baca pesan error dari baris pertama yang relevan.
- Gunakan nama variabel/fungsi yang menjelaskan maksud kode.
- Hindari menyalin kode tanpa memahami input, output, dan efek sampingnya.

**Catatan khusus bab:** Gunakan contoh kecil terlebih dahulu, lalu tingkatkan kompleksitas setelah konsep dasarnya benar.

## 5. Latihan
1. Buat contoh paling sederhana dari konsep bab ini.
2. Ubah satu bagian program dan amati hasilnya.
3. Tambahkan validasi untuk input yang tidak sesuai.
4. Pecah kode menjadi fungsi jika mulai terlalu panjang.
5. Tulis 3 kalimat dengan bahasa sendiri yang menjelaskan konsep ini.

## 6. Kesalahan umum
- Menganggap kode berhasil hanya karena tidak langsung error.
- Tidak menguji kondisi kosong, salah tipe, atau nilai ekstrem.
- Membuat solusi terlalu kompleks untuk masalah sederhana.
- Mengabaikan dokumentasi resmi ketika perilaku fitur belum jelas.

## 7. Checklist penguasaan
- [ ] Bisa menjelaskan konsep tanpa membaca catatan.
- [ ] Bisa membuat contoh kecil dari nol.
- [ ] Bisa membaca dan memperbaiki error yang relevan.
- [ ] Bisa menjelaskan kapan konsep ini tidak diperlukan.
- [ ] Bisa menggunakannya dalam proyek kecil.

## 8. Tantangan
Buat satu program kecil yang menggunakan konsep bab ini bersama minimal dua konsep dari bab sebelumnya. Dokumentasikan input, proses, output, dan satu kasus error yang berhasil kamu tangani.

