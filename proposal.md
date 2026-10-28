# PROPOSAL PROYEK

## Program Rekap dan Analisis Nilai Matematika Kelas

### 1. Judul Proyek

Program Rekap dan Analisis Nilai Matematika Kelas

### 2. Latar Belakang

Pengolahan nilai mahasiswa atau siswa perlu dilakukan dengan teliti
agar hasil rekapitulasi dapat diketahui dengan mudah. Pengolahan nilai
secara manual membutuhkan waktu dan berisiko menimbulkan kesalahan
dalam perhitungan.

Oleh karena itu, dibuat program sederhana menggunakan Python yang
dapat membaca data nilai, memvalidasi nilai, menghitung statistik,
menentukan ketuntasan, serta menyimpan hasil analisis ke dalam file
teks.

### 3. Pengguna dan Tujuan

Pengguna:
- Guru atau pengajar.
- Mahasiswa yang mempelajari pemrograman.
- Pengguna yang membutuhkan rekap nilai sederhana.

Tujuan:
- Membantu proses rekapitulasi nilai.
- Menghitung statistik nilai secara otomatis.
- Menentukan status ketuntasan berdasarkan KKM.
- Menyimpan hasil analisis dalam bentuk laporan.

### 4. Ruang Lingkup

Fitur wajib:
- Membaca data nilai dari file teks.
- Memvalidasi nilai pada rentang 0 sampai 100.
- Menghitung rata-rata, nilai minimum, dan nilai maksimum.
- Menghitung jumlah mahasiswa tuntas dan belum tuntas berdasarkan KKM.
- Menampilkan hasil analisis.
- Menyimpan laporan ke file teks.

Batas proyek:
- Program dijalankan melalui terminal.
- Data disimpan dalam file teks.
- Program tidak menggunakan database.
- Program tidak menggunakan antarmuka grafis.

### 5. Kebutuhan

#### Kebutuhan Fungsional

- Program dapat membaca file data nilai.
- Program dapat memeriksa format data.
- Program dapat memvalidasi nilai.
- Program dapat menghitung statistik nilai.
- Program dapat menentukan status ketuntasan.
- Program dapat menampilkan dan menyimpan laporan.

#### Kebutuhan Nonfungsional

- Program menggunakan bahasa Python.
- Program memiliki struktur kode yang modular.
- Program mudah dijalankan melalui terminal.
- Program menampilkan hasil dengan jelas.
- Program menangani kesalahan yang telah diprediksi.

### 6. IPO

#### Input
- File data nilai mahasiswa.
- Nilai mahasiswa.
- Kriteria Ketuntasan Minimal (KKM).

#### Process
- Membaca data dari file.
- Memeriksa format data.
- Memvalidasi nilai 0 sampai 100.
- Menghitung rata-rata, nilai minimum, dan nilai maksimum.
- Menentukan status ketuntasan.
- Menyusun laporan hasil analisis.

#### Output
- Data nilai yang valid.
- Rata-rata nilai.
- Nilai minimum.
- Nilai maksimum.
- Jumlah mahasiswa tuntas.
- Jumlah mahasiswa belum tuntas.
- Laporan dalam file teks.

### 7. Algoritma

Pseudocode:

MULAI

Baca file data nilai

Jika file tidak ditemukan:
    Tampilkan pesan kesalahan
    SELESAI

Untuk setiap baris data:
    Periksa format data
    Jika format tidak sesuai:
        Lewati data
    Jika nilai tidak berada pada rentang 0 sampai 100:
        Tampilkan pesan validasi
        Lewati data
    Simpan data yang valid

Jika tidak ada data valid:
    Tampilkan pesan bahwa data tidak tersedia
    SELESAI

Hitung rata-rata nilai
Tentukan nilai minimum
Tentukan nilai maksimum

Untuk setiap data mahasiswa:
    Tentukan status berdasarkan KKM

Tampilkan hasil analisis
Simpan laporan ke file teks

SELESAI

### 8. Struktur Program

Program dibagi menjadi beberapa modul:

- main.py
  Mengatur alur utama program.

- data_io.py
  Membaca data nilai dari file.

- analisis.py
  Melakukan validasi nilai, menghitung statistik,
  dan menentukan status ketuntasan.

- utilitas.py
  Menampilkan hasil dan menyimpan laporan.

Struktur folder:

pertemuan-14-proyek-akhir-ziana-2225250076/
├── README.md
├── proposal.md
├── .gitignore
├── data/
│   └── nilai_contoh.txt
├── src/
│   ├── main.py
│   ├── data_io.py
│   ├── analisis.py
│   └── utilitas.py
├── tests/
│   └── test_case.md
└── output/
    └── .gitkeep

### 9. Struktur Data

Struktur data yang digunakan:

- List
  Menyimpan kumpulan data mahasiswa dan nilai.

- Dictionary
  Menyimpan data setiap mahasiswa berdasarkan atribut,
  seperti NIM, nama, dan nilai.

- String
  Menyimpan teks laporan yang akan ditampilkan
  atau ditulis ke file.

- File teks
  Menyimpan data nilai dan laporan hasil analisis.

Contoh model data:

data_mahasiswa = [
    {"nim": "A001", "nama": "Ayu", "nilai": 85},
    {"nim": "A002", "nama": "Budi", "nilai": 78}
]

### 10. Test Case

Test case disusun pada file:

tests/test_case.md

Test case mencakup kategori normal, batas, dan invalid,
dengan jumlah minimal lima kasus.

### 11. Pembagian Tugas

| Peran | Tanggung Jawab | PIC |
|---|---|---|
| Koordinator | Menjaga ruang lingkup dan integrasi proyek | [Nama] |
| Programmer Data I/O | Membaca dan menulis file serta validasi data | [Nama] |
| Programmer Logika | Menghitung statistik dan fungsi matematika | [Nama] |
| Tester/QA | Menyusun dan menjalankan test case | [Nama] |
| Dokumentasi | Membuat README dan dokumentasi penggunaan | [Nama] |

Catatan:
Satu orang dapat memegang lebih dari satu peran.
Semua anggota tetap memahami alur proyek secara keseluruhan.

### 12. Jadwal

| Waktu | Target |
|---|---|
| Pertemuan 14 | Proposal, struktur repository, pseudocode, test case, dan pembagian tugas |
| Antara Pertemuan 14–15 | Implementasi awal fitur wajib |
| Pertemuan 15 | Integrasi, testing, debugging, dan dokumentasi |
| Pertemuan 16 | Presentasi, demonstrasi, dan evaluasi proyek |

### 13. Repository

Nama repository:
pertemuan-14-proyek-akhir-ziana-2225250076

URL GitHub:
https://github.com/zianaaaz-commits/pertemuan-14-proyek-akhir-ziana-2225250076.git