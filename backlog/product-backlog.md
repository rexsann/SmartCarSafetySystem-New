# Product Backlog — Smart Car Safety

## Deskripsi Proyek

Smart Car Safety adalah sistem pemantauan gas karbon monoksida (CO) di dalam kabin mobil menggunakan ESP32 dan sensor MQ-7. Sistem dirancang untuk membaca kadar CO, memberikan peringatan ketika kadar gas melewati ambang batas, dan mendukung pemantauan kondisi kabin.

## Product Backlog

| ID | User Story | Prioritas | Kriteria Penerimaan |
|---|---|---|---|
| PB-01 | Sebagai pengendara, saya ingin sistem membaca kadar CO secara real-time agar kondisi kabin dapat dipantau. | Tinggi | Data kadar CO dapat dibaca dari sensor yang terhubung ke ESP32. |
| PB-02 | Sebagai pengendara, saya ingin sistem membandingkan kadar CO dengan ambang batas agar tingkat bahaya dapat diketahui. | Tinggi | Sistem menentukan status berdasarkan ambang batas yang dikonfigurasi. |
| PB-03 | Sebagai pengendara, saya ingin indikator LED menunjukkan status keamanan agar saya dapat mengetahui kondisi kabin. | Tinggi | LED menampilkan status sesuai logika sistem. |
| PB-04 | Sebagai pengendara, saya ingin buzzer aktif saat kadar CO melewati ambang batas agar saya mendapat peringatan langsung. | Tinggi | Buzzer aktif ketika kondisi bahaya terdeteksi. |
| PB-05 | Sebagai pengendara, saya ingin data dikirim ke Blynk IoT agar kondisi kabin dapat dipantau melalui smartphone. | Tinggi | Data monitoring dikirim melalui koneksi Wi-Fi ke Blynk IoT. |
| PB-06 | Sebagai pengendara, saya ingin melihat kadar CO dan status keamanan pada dashboard agar dapat memantau kondisi kabin. | Sedang | Dashboard menampilkan data dan status yang diterima. |
| PB-07 | Sebagai pengendara, saya ingin menerima notifikasi ketika kadar CO melewati ambang batas agar dapat segera mengambil tindakan. | Tinggi | Notifikasi dikirim ketika kondisi bahaya terdeteksi dan koneksi tersedia. |
| PB-08 | Sebagai pengendara, saya ingin melihat kadar CO pada OLED agar informasi tersedia langsung di perangkat. | Sedang | OLED menampilkan nilai CO yang diperbarui secara berkala. |
| PB-09 | Sebagai pengembang, saya ingin menguji fungsi pembacaan sensor dan alarm agar perilaku sistem dapat diverifikasi. | Sedang | Pengujian dilakukan dan hasilnya dicatat. |
| PB-10 | Sebagai tim pengembang, kami ingin mendokumentasikan proses pengembangan agar pekerjaan mudah ditinjau dan dilanjutkan. | Sedang | Dokumentasi backlog, sprint, dan kontribusi tersedia di repository. |

## Catatan

Prioritas dan kriteria penerimaan dapat diperbarui berdasarkan hasil diskusi tim, kebutuhan proyek, dan hasil pengujian. Ambang batas CO harus ditentukan berdasarkan sumber teknis yang sesuai dan tidak boleh ditetapkan sembarangan.
