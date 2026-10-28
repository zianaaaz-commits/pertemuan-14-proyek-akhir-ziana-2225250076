# Test Case Proyek

## Program Rekap dan Analisis Nilai Matematika Kelas

| ID | Kategori | Input/Kondisi | Expected Result |
|---|---|---|---|
| TC01 | Normal | Nilai 80, 70, 90 | Rata-rata nilai adalah 80 |
| TC02 | Batas | Nilai 0 | Diterima sebagai nilai valid |
| TC03 | Batas | Nilai 100 | Diterima sebagai nilai valid |
| TC04 | Invalid | Nilai 105 | Ditolak dengan pesan validasi |
| TC05 | Invalid | File tidak ditemukan | FileNotFoundError ditangani |
| TC06 | Normal | Semua nilai >= KKM | Jumlah mahasiswa tuntas sama dengan jumlah data |

## Definition of Done

- [ ] Semua fitur wajib berjalan.
- [ ] Semua test case wajib lulus.
- [ ] Program tidak berhenti karena error yang sudah diprediksi.
- [ ] Output mudah dibaca.
- [ ] README menjelaskan cara menjalankan program.
- [ ] Commit proyek menunjukkan kontribusi tim.