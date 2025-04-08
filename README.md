# Dashboard-Ruang-Gawat-Darurat-Rumah-Sakit-PowerBI

## Tujuan Projek
Untuk meningkatkan efisiensi operasional dan memberikan wawasan yang dapat ditindaklanjuti terkait kinerja ruangan gawat darurat, kita perlu membuat Dashboard Ruang Gawat Darurat Rumah Sakit menggunakan Power BI. Solusi ini akan memungkinkan para pemangku kepentingan untuk memantau, menganalisis, dan mengambil keputusan berbasis data terkait manajemen pasien dan optimalisasi layanan.

## Dataset yang Digunakan
- <a href="https://github.com/ifanapridarahman/Dashboard-Ruang-Gawat-Darurat-Rumah-Sakit-PowerBI/blob/main/Hospital%20ER_Data.xlsx">Dataset</a>

## Dashboard Interaktif
- <a href="https://github.com/ifanapridarahman/Dashboard-Ruang-Gawat-Darurat-Rumah-Sakit-PowerBI/blob/main/Dashboard%20Ruang%20Gawat%20Darurat%20Rumah%20Sakit.pbix">Dashboard Interaktif</a>

## Persyaratan KPI
1. **Jumlah Pasien**
   - Menghitung total jumlah pasien yang mengunjungi IGD setiap hari.
   - Menampilkan tren harian menggunakan *area sparkline* untuk memahami pola dari waktu ke waktu, seperti hari-hari puncak atau tren musiman.
2. **Rata-Rata Waktu Tunggu**
   - Menghitung rata-rata waktu tunggu pasien sebelum ditangani oleh tenaga medis.
   - Menggunakan *area sparkline* untuk menunjukkan fluktuasi harian dan mengidentifikasi hari dengan waktu tunggu yang lebih lama yang mungkin memerlukan penyesuaian operasional.
3. **Skor Kepuasan Pasien**
   - Menganalisis skor rata-rata kepuasan pasien setiap hari untuk mengevaluasi kualitas layanan yang diberikan
   - Menampilkan tren harian menggunakan *area sparkline* untuk mengidentifikasi penurunan kepuasan dan hubungkan dengan tantangan operasional atau waktu-waktu sibuk.
4. **Jumlah Pasien yang Dirujuk**
   - Menghitung jumlah pasien yang ditujuk ke departemen tertentu dari IGD setiap hari.
   - Menggunakan *area sparkline* untuk melacak tren harian dan mengidentifikasi departemen dengan tingkat rujukan tinggi, yang mungkin memerlukan tambahan sumber daya.

## Dashboard 1 : Tampilan Bulanan (Bulan Februari)
Memantau metrik utama dan tren secara bulanan untuk mengidentifikasi pola dan area yang perlu ditingkatkan. Grafik yang perlu dibuat:
- Status Penerimaan Pasien : Melacak jumlah pasien yang diterima dan pasien yang tidak diterima
- Distribusi Usia Pasien : Mengelompokkan pasien berdasarkan rentang usia 10 tahun.
- Rujukan Departemen : Analisis tren rujukan ke berbagai departemen
- Ketepatan waktu : Mengukur persentase pasien yang dilayani dalam waktu 30 menit
- Analisis Jenis Kelamin : Memvisualisasikan distribusi pasien berdasarkan jenis kelamin.
- Demografi Ras : Analisis data pasien berdasarkan ras.
- Analisis waktu : Mengevaluasi volume pasien berdasarkan hari dan jam
- <a href="https://github.com/ifanapridarahman/Dashboard-Ruang-Gawat-Darurat-Rumah-Sakit-PowerBI/blob/main/Dashboard%20Ruang%20Gawat%20Darurat%20Rumah%20Sakit_Tampilan%20Bulanan.jpg">Dashboard 1</a>
![Dashboard Ruang Gawat Darurat Rumah Sakit_Tampilan Bulanan](https://github.com/user-attachments/assets/17284b22-324b-4efb-8678-02013ffc7cbf)

**Insight**
1. **Jumlah Pasien**
   - Total 431 pasien dilayani selama bulan Februari
   - Ini menunjukkan tingkat kunjungan yang cukup tinggi untuk ruang gawat darurat.
2. **Waktu Tunggu dan Tingkat Kepuasan**
   - Rata-rata waktu tunggu adalah 36,7 menit
      - Hanya 34,34% pasien yang menunggu di bawah 30 menit
      - Artinya, lebih dari setengah pasien masih harus menunggu lebih lama dari target. Area inilah yang perlu ditingkatkan
   - Skor Kepuasan pasien cukup rendah : 4,72 dari 10. Menunjukkan bahwa pengalaman pasien yang masih belum optimal
3. **Demografi Pasien**
   - Usia terbanyak : Kelompok 30 - 39 tahun sebanyak 66 pasien, diikuti oleh kelompok 30-39 dan 40-49 sebanyak masing-masing 65 pasien.
   - Jenis Kelamin : Perempuan (45,01%) & Laki-laki (54,29%)
   - Distribusi ras : Terbanyak pasien ras putih (124 orang), diikuti oleh ras Africa-Amerika dan Multi ras dengan masing-masing sebanyak 89 orang
4. **Status Penerimaan dan Rujukan**
   - 51.97% pasien diterima (224 orang) dan 48.03% pasien tidak diterima (207 orang)
   - Rujukan terbanyak : Tidak dirujuk (252 pasien), Praktik Umum (89 orang), dan ortopedi (46 orang)
5. **Periode Sibuk (Jam & Hari)**
   - Hari tersibuk : Kamis (77 pasien), diikuti oleh Rabu (67) dan minggu (62)
   - Jam Sibuk : 11.00-12.00 dan 19.00-20.00, juga pada malam hari jam 23.00-24.00
   - Perlu peningkatan jumlah staf dan sumber daya di jam-jam ini.

**Kesimpulan & Rekomendasi**
- Perlu perbaikan pada efisiensi layanan untuk mengurangi waktu tunggu
- Skor kepuasan masih rendah, evaluasi prosedur dan pengalaman pasien
- Jam dan hari sibuk harus diantisipasi dengan penjadwalan staf yang lebih strategis
- Fokus pelayanan bisa diarahkan ke kelompok usia lanjut dan dewasa produktif, karena mendominasi
