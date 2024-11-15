# Diagonal Magic Cube Solver
## Deskripsi 

Program ini bertujuan untuk menemukan solusi bagi **Diagonal Magic Cube** berukuran 5×5×5, yaitu kubus angka 1 hingga \(n^3\) (tanpa pengulangan) yang memenuhi sifat-sifat:

1. **Magic Number**: Satu angka khusus yang menjadi acuan jumlah pada tiap baris, kolom, dan diagonal.
2. **Keseimbangan Baris, Kolom, dan Tiang**: Jumlah angka pada setiap baris, kolom, dan tiang harus sama dengan magic number.
3. **Diagonal Ruang dan Bidang**: Jumlah angka pada semua diagonal ruang dan bidang dalam kubus harus sama dengan magic number.

Kubus dimulai dari susunan acak, dan pencarian solusi dilakukan melalui beberapa metode **local search**, meliputi Steepest Ascent Hill-Climbing, Hill-Climbing with Sideways Move, Random Restart, Stochastic Hill-Climbing, Simulated Annealing, dan Genetic Algorithm.

Proyek ini juga mencakup eksperimen untuk membandingkan efektivitas masing-masing metode dalam menemukan solusi yang memenuhi sifat-sifat Diagonal Magic Cube.

## Struktur File

- **/src**: Berisi implementasi metode local search.
- **/doc**: Berisi file laporan.

## Cara Menjalankan

1. Clone repositori ini dan navigasikan ke direktori proyek.
2. Klik 'Run All' pada file **`main.ipynb`** untuk memulai eksperimen dengan konfigurasi default.
3. Apabila menggunakan VSCode, input masukan pada **search bar** di bagian atas ketika diminta input.
4. Hasil eksperimen akan muncul di file yang sama.

## Pembagian Tugas

| NIM      | Nama                                        | Tugas   |
|-------------------|----------------------------------------------|--------------------------|
| 18222002       | Yasra Zhafirah       |Membuat program source code, README.md.
| 18222030       | Vini Putiasa |Membuat fungsi objektif, mengerjakan pembahasan implementasi algoritma, pembahasan hasil eksperimen dan analisis pertanyaan, kesimpulan.         |
| 18222031       | Benedicta Eryka Santosa |Mengerjakan pembahasan.        |
| 18222090       | Kerlyn Deslia Andeskar |Mengerjakan deskripsi persoalan, pembahasan, kesimpulan & saran, fungsi ascii.       |
