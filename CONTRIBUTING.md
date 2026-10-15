# Contribution Guide — Smart Car Safety

## 1. Tujuan

Dokumen ini menjadi panduan bagi anggota tim dalam berkontribusi pada proyek Smart Car Safety melalui GitHub agar perubahan kode dan dokumentasi terorganisasi, mudah ditinjau, dan tidak saling mengganggu.

## 2. Struktur Branch

| Branch | Fungsi |
|---|---|
| `main` | Menyimpan versi utama proyek yang stabil. |
| `develop` | Menjadi branch integrasi pekerjaan tim sebelum perubahan masuk ke `main`. |
| `feature/nama-fitur` | Digunakan untuk mengembangkan fitur tertentu. |
| `docs/nama-dokumentasi` | Digunakan untuk mengerjakan dokumentasi. |
| `fix/nama-perbaikan` | Digunakan untuk memperbaiki kesalahan. |

Contoh branch:
- `feature/baca-mq7`
- `docs/agile-documentation`
- `fix/alarm-buzzer`

## 3. Alur Kerja

1. Pilih atau buat branch pekerjaan berdasarkan jenis tugas.
2. Kerjakan perubahan hanya pada branch tersebut.
3. Periksa kembali file yang berubah sebelum membuat commit.
4. Simpan perubahan dengan commit message yang jelas.
5. Push perubahan ke repository GitHub.
6. Buat Pull Request dengan `develop` sebagai base untuk pekerjaan fitur atau dokumentasi.
7. Periksa perubahan dan lakukan review sebelum merge.
8. Gabungkan Pull Request setelah perubahan dinyatakan sesuai.

Perubahan dari `develop` ke `main` dilakukan setelah integrasi dan pengujian sesuai dengan kesepakatan tim.

## 4. Aturan Commit

Gunakan pesan commit yang singkat, jelas, dan menjelaskan tujuan perubahan.

Contoh:
- `docs: add product backlog`
- `docs: add sprint backlog`
- `docs: add contribution guide`
- `feat: implement MQ-7 reading`
- `fix: correct buzzer threshold`

Gunakan awalan `docs` untuk dokumentasi, `feat` untuk fitur baru, `fix` untuk perbaikan, dan `test` untuk pengujian.

## 5. Aturan Pull Request

Setiap Pull Request sebaiknya:
- Memiliki judul yang menjelaskan perubahan.
- Memiliki deskripsi tentang tujuan dan isi perubahan.
- Mengarah ke base branch yang sesuai.
- Hanya memuat perubahan yang berkaitan dengan pekerjaan tersebut.
- Diperiksa sebelum merge.
- Tidak menggabungkan perubahan yang belum disetujui berdasarkan aturan tim.

## 6. Pemeriksaan Sebelum Merge

Sebelum merge, pastikan:
- Tidak ada file yang tidak sengaja ikut berubah.
- Perubahan sesuai dengan tujuan Pull Request.
- Dokumentasi sudah diperiksa atau pengujian sudah dilakukan sesuai jenis perubahan.
- Tidak ada konflik yang belum diselesaikan.
- Review dan persetujuan sudah dipenuhi jika diwajibkan.

## 7. Kolaborasi Tim

Anggota tim perlu memperbarui status pekerjaan, menyampaikan kendala, dan berkoordinasi ketika ada perubahan yang memengaruhi pekerjaan anggota lain.

Panduan ini dapat disesuaikan berdasarkan kesepakatan tim dan ketentuan tugas.
