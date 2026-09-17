# Pertemuan 03 Seleksi Python

Nama: Suchita Rahma Fakhira
NIM: 2225250006
Kelas: 3B

## Tujuan

Memahami dan menerapkan seleksi dalam Python menggunakan if, if-else, if-elif-else, kondisi majemuk, dan nested if.

## Cara Menjalankan

Program dapat dijalankan melalui terminal VS Code dengan perintah:

python nama_file.py

Contoh:

python latihan/01_genap_ganjil.py
python latihan/02_bandingkan_bilangan.py
python latihan/03_kelulusan.py
python latihan/04_jenis_segitiga.py
python tugas/analisis_persamaan_kuadrat.py

## Algoritma Latihan

### Latihan 1 – Genap atau Ganjil

1. Masukkan sebuah bilangan.
2. Hitung sisa pembagian bilangan dengan 2.
3. Jika sisanya 0, tampilkan "Genap".
4. Jika tidak, tampilkan "Ganjil".

### Latihan 2 – Membandingkan Dua Bilangan

1. Masukkan dua bilangan.
2. Bandingkan kedua bilangan.
3. Jika bilangan pertama lebih besar, tampilkan bilangan pertama lebih besar.
4. Jika bilangan kedua lebih besar, tampilkan bilangan kedua lebih besar.
5. Jika keduanya sama, tampilkan bahwa kedua bilangan sama.

### Latihan 3 – Kelulusan Bersyarat

1. Masukkan nilai akhir dan persentase kehadiran.
2. Periksa apakah nilai minimal 60 dan kehadiran minimal 80%.
3. Jika kedua syarat terpenuhi, tampilkan "Lulus".
4. Jika salah satu syarat tidak terpenuhi, tampilkan "Belum lulus".

### Latihan 4 – Jenis Segitiga

1. Masukkan tiga panjang sisi.
2. Periksa apakah ketiga sisi dapat membentuk segitiga.
3. Jika tidak, tampilkan "Bukan segitiga".
4. Jika ketiga sisi sama, tampilkan "Segitiga sama sisi".
5. Jika dua sisi sama, tampilkan "Segitiga sama kaki".
6. Jika semua sisi berbeda, tampilkan "Segitiga sembarang".

## Algoritma Tugas

### Tugas 2 – Analisis Persamaan Kuadrat

1. Masukkan nilai a, b, dan c.
2. Periksa nilai a.
3. Jika a = 0, tampilkan bahwa bukan persamaan kuadrat.
4. Jika a ≠ 0, hitung diskriminan dengan rumus D = b² - 4ac.
5. Jika D > 0, tampilkan bahwa terdapat dua akar real berbeda.
6. Jika D = 0, tampilkan bahwa terdapat satu akar real kembar.
7. Jika D < 0, tampilkan bahwa tidak terdapat akar real.

## Hasil Pengujian

### Latihan 1 – Genap atau Ganjil

1. Input 8 → Genap
2. Input 13 → Ganjil
3. Input 0 → Genap
4. Input -7 → Ganjil

### Latihan 2 – Membandingkan Dua Bilangan

1. Input 7 dan 4 → Bilangan pertama lebih besar
2. Input 2 dan 9 → Bilangan kedua lebih besar
3. Input 5 dan 5 → Kedua bilangan sama
4. Input -3 dan -8 → Bilangan pertama lebih besar

### Latihan 3 – Kelulusan Bersyarat

1. Nilai 75, kehadiran 90% → Lulus
2. Nilai 59, kehadiran 90% → Belum lulus
3. Nilai 75, kehadiran 79% → Belum lulus
4. Nilai 60, kehadiran 80% → Lulus

### Latihan 4 – Jenis Segitiga

1. Input 3, 3, 3 → Segitiga sama sisi
2. Input 5, 5, 8 → Segitiga sama kaki
3. Input 3, 4, 5 → Segitiga sembarang
4. Input 1, 2, 3 → Bukan segitiga

### Tugas 2 – Analisis Persamaan Kuadrat

1. Input a=1, b=-5, c=6 → D=1 → Dua akar real berbeda.
2. Input a=1, b=2, c=1 → D=0 → Satu akar real kembar.
3. Input a=1, b=0, c=1 → D=-4 → Tidak memiliki akar real.
4. Input a=0, b=2, c=3 → Bukan persamaan kuadrat.

## Refleksi

Setelah mengerjakan tugas ini, saya lebih memahami penggunaan percabangan dalam Python. Saya juga belajar menentukan kondisi yang sesuai dengan input dan melakukan pengujian untuk memastikan hasil program sudah benar.
Kesulitan yang saya alami adalah menentukan kondisi pada setiap percabangan. Setelah mencoba beberapa test case, saya menjadi lebih memahami bagaimana program mengambil keputusan berdasarkan kondisi yang diberikan.
Dari tugas ini, saya menyadari bahwa membuat program tidak hanya menulis kode, tetapi juga perlu memahami algoritma dan melakukan pengujian agar program berjalan sesuai tujuan.