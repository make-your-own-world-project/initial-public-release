> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Apa yang Sedang Berjalan Sekarang

![Mesin lokal diorganisir berdasarkan tanggung jawab di sekitar tulang punggung yang dikendalikan bersama](../../assets/public-machinery-catalog.png)

## Cara membaca katalog ini

Katalog adalah mitra publik dari tampilan Pusat Data di Mission Control. Ini menjelaskan kontribusi setiap roda gigi dan apa yang akan hilang jika hilang, tanpa mempublikasikan alamat pribadi, tata letak mesin, kredensial, jalur file, atau irama operasi. Grafik langsung tetap menjadi sumber kebenaran operasional.

Status komponen penting. Suatu alat mungkin aktif, dipertahankan sebagai sistem sumber, dievaluasi tetapi tidak diadopsi, atau pendahulunya sudah tidak digunakan lagi. Kehadiran dalam katalog ini tidak memberikan otoritas komponen di luar perannya yang dinyatakan.

Aturan itu mencakup kemampuan perbatasan eksternal. Saat digunakan, ia menempati stasiun yang dibatasi dan menerima muatan yang dibuat khusus daripada akses tidak terbatas ke korpus yang dikelola. Payload tersebut mendukung operasi yang dinyatakan tetapi menghilangkan status tahan lama yang diperlukan untuk merekonstruksi sistem yang lebih luas atau secara mandiri melakukan penarikan di masa depan. Stasiun tersebut menerima pekerjaan, bukan penyimpanan catatan manusia yang dapat dimanfaatkan oleh lembaga terpusat untuk mendapatkan nilai jangka panjang.

## Cara masuk dan mengelilingi sistem

### Otak Robot (LibreChat)


**Tanggung Jawab.** Menyediakan jendela percakapan menghadap manusia yang dapat diganti. Ini membawa permintaan dan tanggapan sementara memori tahan lama, pengambilan, penalaran, dan verifikasi tetap berada dalam layanan di bawahnya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[Obrolan Libre](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Pemisah Percakapan


**Tanggung jawab.** Pemberitahuan ketika obrolan berubah menjadi dua subjek dan menawarkan untuk mengajukan topik yang sudah selesai secara terpisah.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[API Cepat](https://github.com/fastapi/fastapi)

### Kontrol Misi


**Tanggung jawab.** Jendela ke mesin: apa yang sedang berjalan, apa yang memerlukan perhatian, dan apa yang sedang dilakukannya saat ini. Pada batas publikasi ini, halaman statusnya melaporkan semua sistem yang dipantau beroperasi pada instalasi lokal.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Status operasional melaporkan status layanan; artefak dan tanda terima yang diterima menetapkan batasan eksekusi dan bukti semantik yang terpisah.

**Alat publik utama.**[API Cepat](https://github.com/fastapi/fastapi),[Grafikviz](https://gitlab.com/graphviz/graphviz),[Psikopg](https://github.com/psycopg/psycopg)

### Router Semantik


**Tanggung jawab.** Merutekan permintaan yang dibatasi ke mesin lokal yang sesuai dan memerlukan otorisasi eksplisit sebelum menggunakan inferensi eksternal. Kemampuan mahal dipilih hanya ketika permintaan membenarkan biaya yang diukur.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[API Cepat](https://github.com/fastapi/fastapi). Envoy dan vLLM Semantic Router tetap dikreditkan dalam indeks sumber sebagai pendahulunya yang diperiksa atau dihentikan, bukan dependensi runtime saat ini.

### Riwayat Agen Lengkap


**Tanggung jawab.** Pertahankan aliran peristiwa agen yang lengkap dan terurut sebagai bukti interaksi, termasuk pergantian manusia, pergantian asisten, alat, kesalahan, dan koreksi. Sejarah mencatat apa yang terjadi; mereka tidak mengubah pernyataan agen menjadi fakta yang terverifikasi.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya menyediakan apa yang menjadi sumber dan asal usulnya; interpretasi hilir tetap terpisah.

### Dokumen Proyek


**Tanggung jawab.** Melestarikan desain pribadi, bukti, dan catatan proyek yang menjelaskan alasan platform ini ada dan bagaimana arsitekturnya berubah. Produk publik menggunakan turunan yang ditinjau daripada mengekspos lokasi dokumen pribadi.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya menyediakan apa yang menjadi sumber dan asal usulnya; interpretasi hilir tetap terpisah.

### Vikunja


**Tanggung jawab.** Mempertahankan sistem tugas eksternal sebagai sumber yang dimiliki secara independen sebelum platform ini ada. Integrasi dapat membaca bukti tugas resmi tanpa menyerap sistem tugas ke dalam korpus atau mengubah siklus hidupnya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya menyediakan apa yang menjadi sumber dan asal usulnya; interpretasi hilir tetap terpisah.

**Alat publik utama.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Pelestarian dan pengambilan

### Asupan Pengetahuan


**Tanggung jawab.** Cara masuknya. Jatuhkan dokumen, ekspor, setumpuk catatan, dan dokumen itu akan mendarat di suatu tempat yang mudah ditemukan, bukan di mana pun.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### MongoDB


**Tanggung jawab.** Mengadakan percakapan itu sendiri, seperti yang dikatakan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Ketersediaan dan integritas diperlukan; data yang disimpan tidak menafsirkan atau memverifikasi dirinya sendiri.

**Alat publik utama.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Tanggung jawab.** Menyimpan catatan proyek terstruktur yang tahan lama, status turunan, dan indeks pencarian yang dimaksudkan untuk bertahan lebih lama dari layanan aplikasi yang dapat diganti. Catatan yang disimpan mempunyai otoritas dan sumber yang berbeda dan bukannya menjadi satu memori yang tidak dapat dibedakan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Ketersediaan dan integritas diperlukan; data yang disimpan tidak menafsirkan atau memverifikasi dirinya sendiri.

**Alat publik utama.**[PostgreSQL](https://github.com/postgres/postgres),[vektor pg](https://github.com/pgvector/pgvector)

## Penalaran dan rekonstruksi

### Pengklasifikasi Relasi Argumen

menyematkan klasifikasi CPU AMF_ARI OpenVINO berdasarkan inferensi, konflik, penyusunan ulang, atau tidak ada hubungan

**Tanggung jawab.** Mengklasifikasikan hubungan antara dua proposisi yang diberikan; itu tidak menciptakan proposisi atau menyimpulkan motif pribadi. Contoh: membedakan satu pernyataan yang mendukung pernyataan lain dari pernyataan yang bertentangan, atau tidak menghasilkan relasi yang didukung.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[Model AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Artefak Manusia


**Tanggung jawab.** Menentukan produk yang dapat dibuat oleh manusia yang dapat dibuat oleh jalur perakitan. Setiap produk memiliki penerima, tujuan, struktur, kebijakan bukti, dan kontrak pengirimannya sendiri, bukan berbagi satu garis besar yang umum.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Grounding + Validasi Pengiriman

gerbang penerimaan independen atas pemeriksaan kesetiaan, asal, kehilangan, penemuan, tenunan, dan pemahaman

**Tanggung jawab.** Periksa secara independen apakah artefak mempertahankan makna yang didukung dan memenuhi kontrak pengiriman yang dinyatakan sebelum dirilis. Contoh: menolak paragraf yang dapat dibaca yang menghasilkan kesimpulan, dan secara terpisah menolak dokumen dasar yang strukturnya tidak dapat digunakan oleh pembaca sasarannya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Resolusi Audiens

status penerima, prasyarat, register, dan relevansi

**Tanggung jawab.** Uraikan apa yang diharapkan diketahui, dibutuhkan, dan ditoleransi oleh penerima, sekaligus menjaga asumsi tetap eksplisit. Contoh: memerlukan panduan pemilik rumah untuk menjelaskan pH sebelum menggunakan singkatan yang familiar bagi teknisi kolam.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Runtuhnya Pohon Utuh + Paket

partisi, seleksi, keuntungan, dan kerugian yang dibatasi kontainer

**Tanggung jawab.** Pilih dan seimbangkan apa yang sesuai dengan artefak yang diminta sambil mencatat apa yang dihilangkan dan mempertahankan bentuk pohon yang bermakna. Contoh: pertahankan agar setiap cabang utama terwakili dalam artikel 1.000 kata daripada membiarkan cabang sumber terbesar menghabiskan seluruh anggaran.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[submodlib](https://github.com/decile-team/submodlib),[berlutut](https://github.com/arvkevi/kneed)

### Model Kerja Kompak

pembawa dengan cakupan permintaan portabel untuk unit, relasi, lintasan, blok sumber, rencana, pegangan, dan buku besar handoff yang dipilih

**Tanggung jawab.** Kemas fakta, hubungan, kronologi, ketidakpastian, kegagalan, dan sumber yang dipilih ke dalam konteks spesifik pekerjaan portabel. Contoh: berikan rantai pemeliharaan kumpulan kepada editor dan mengapa langkah-langkahnya terhubung tanpa memuat seluruh korpus atau menghapus tautan.

**Harus dipertahankan.** source_spans; relasi_id; kronologi; ketakpastian; kegagalan; supersesi; tidak diketahui

**Bentuk sumber daya.** CPU dan RAM sebanding dengan pilihan yang dibatasi; tidak ada GPU atau sewa

**Batas.** kualitas dibatasi oleh hubungan hulu dan cakupan negara simpanan

### Mekanisme Pengiriman

register, mode, profil tenunan, kecepatan, kepadatan, dan kontrol deslop

**Tanggung jawab.** Kendala pengiriman terukur pasokan, seperti tempo, kepadatan, register, dan lintasan tenun, untuk produk dan audiens ini. Contoh: memberikan penjelasan kepada anak-anak dengan paket yang lebih pendek dan pola pengulangan yang berbeda dari laporan teknis tanpa mengubah fakta yang mendasarinya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Pemrosesan Awal Wacana

irisan berbatas tepat, kandidat referensi FastCoref, dan tautan operan isanlp RST yang disewakan

**Tanggung jawab.** Identifikasi referensi kandidat dan rentang wacana sebelum melakukan klasifikasi penalaran sambil mempertahankan koordinat sumber yang tepat. Contoh: tautkan 'itu' ke kandidat pompa yang disebutkan dan paparkan dua klausa yang digabungkan dengan relasi wacana sebab akibat.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[IsaNLP Pertama](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Rekonstruksi Maju Seluruh Artefak

prasyarat, acuan, perekat sebab akibat, perkembangan, pendahuluan, dan kesimpulan

**Tanggung jawab.** Susun kembali materi yang dipilih sesuai urutan pembaca, pulihkan prasyarat, referensi, hubungan sebab akibat, perkembangan, dan akhir yang jujur. Contoh: perkenalkan tujuan sebelum prosedur dan tutup pertanyaan yang belum terselesaikan jika tidak ada kesimpulan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Grafik Mengapa dan Proyeksi Ketergantungan

pandangan deterministik dari tepi grafik rahasia yang tidak dapat menimbulkan klaim penalaran baru

**Tanggung jawab.** Terjemahkan tepi relasi yang diterima menjadi ketergantungan yang dapat diperiksa dan alasannya dilihat tanpa menambahkan interpretasi. Contoh: tunjukkan bahwa kesimpulan B bergantung pada premis A karena sisi klasifikasi yang tepat itu ada.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[JaringanX](https://github.com/networkx/networkx)

### Jawaban Interaktif Beralas


**Tanggung jawab.** Menampilkan jawaban percakapan dengan alasan, asal, ketidakpastian, dan jalur perluasan yang relevan. Jalur jawabannya mungkin melintasi percakapan lengkap dan siklus hidup bukti tanpa berpura-pura menjadi proses pembuatan dokumen.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Jembatan Protokol Manusia

pengkodean berorientasi penerima dari muatan tetap yang didukung

**Tanggung jawab.** Mengonversi muatan tetap dan didukung menjadi bentuk yang dapat diikuti oleh orang yang dituju, menggunakan kontrak produk dan pola pengiriman terukur; itu tidak dapat mengubah bukti. Contoh: mengubah rantai penalaran yang sama menjadi email ringkas atau panduan bertahap dengan mengubah struktur penyampaian, bukan kesimpulan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Majelis Konteks Interaktif


**Tanggung jawab.** Buat bukti terbatas dan grafik alasan untuk pertanyaan saat ini, dengan menjaga kronologi, koreksi, kegagalan, identitas sumber, dan otorisasi. Ini memberikan konteks pada jawaban tanpa meratakan korpus ke dalam cuplikan pencarian.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Aksesi Tanpa Rugi


**Tanggung jawab.** Akui byte asli dan peristiwa asli sebelum interpretasi, dan hanya mencatat fakta kedatangan yang diamati. Deskripsi, stempel waktu yang disimpulkan dari konten, identitas, dan hubungan tetap merupakan pengamatan berversi terpisah.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Bukti Utama


**Tanggung jawab.** Memegang jaminan resmi yang nantinya harus dapat ditelusuri kembali oleh representasi dan produk. Keberadaan mereka tetap bertahan bahkan ketika sistem belum dapat menjelaskan makna atau hubungannya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Pohon Sementara Lengkap

bukti lengkap sebelum pemangkasan, ketergantungan, alternatif, dan struktur kegagalan

**Tanggung jawab.** Memegang pohon kandidat lengkap dengan cakupan permintaan, termasuk alternatif, kegagalan, hal yang tidak diketahui, dan tampilan yang digantikan, sehingga penciutan dapat melihat apa yang akan hilang. Contoh: simpan perawatan yang gagal dan koreksi selanjutnya sebelum memilih bahan untuk panduan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Grafik Penalaran

kronologi, hubungan yang diketik, siklus hidup klaim, kegagalan, dan ketidakpastian

**Tanggung jawab.** Pertahankan peta cakupan permintaan yang berisi proposisi, kronologi, upaya, hasil, konflik, ketergantungan, dan ketidakpastian. Contoh: menghubungkan perlakuan yang gagal dengan koreksi yang menggantikannya tanpa menghapus status mana pun.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Permintaan + Kontrak Artefak

tujuan, penerima, wadah, saluran, anggaran, dan kebenaran

**Tanggung jawab.** Membekukan tujuan, penerima, produk, saluran, anggaran, dan standar kebenaran sehingga setiap roda hilir menyelesaikan pekerjaan yang sama. Contoh: bedakan penjelasan pembaca umum sepanjang 500 kata dari laporan insiden teknis sebelum pemilihan bukti dimulai.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Ekspansi Terbalik

berkumpul mundur tanpa memangkas; mengukur kontribusi marjinal

**Tanggung jawab.** Berangkat dari permintaan atau bukti selanjutnya menuju catatan terkait sebelumnya dan kumpulkan perjalanan kandidat secara lengkap sebelum semuanya dibuang. Contoh: ikuti kembali pertanyaan alga saat ini melalui catatan pH sebelumnya, ukuran kolam, pemeliharaan, dan konteks penggunaan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Gerakan Retoris yang Diketik

pekerjaan semantik dan ketergantungan, tidak pernah menuju substring

**Tanggung jawab.** Tetapkan pekerjaan komunikatif dan ketergantungan pada setiap unit yang dipilih berdasarkan kontrak produk, bukan kata judul yang cocok. Contoh: tandai bukti sebagai pendukung suatu klaim dan kegagalan sebagai penyiapan pemulihan, bukan menyebut keduanya sebagai 'latar belakang'.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Rekonstruksi Semantik

entitas, proposisi, episode, upaya, hasil, dan pertanyaan

**Tanggung jawab.** Ubah observasi sumber menjadi objek semantik yang diatribusikan tanpa menentukan kepentingan akhir atau presentasinya. Contoh: mewakili usulan perbaikan, upaya, kegagalannya, dan pertanyaan yang tersisa sebagai rekaman tertaut terpisah.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Representasi Berversi


**Tanggung jawab.** transkrip, struktur, teks, OCR, tata letak, dan tampilan turunan

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Mengapa Itu Penting

mengaitkan motivasi, perhatian, konsekuensi, dan relevansi saat ini

**Tanggung jawab.** Bawalah bukti yang diatribusikan secara langsung dan eksplisit tentang alasan perhatian diberikan, dan biarkan alasan yang tidak didukung tidak diketahui. Contoh: pertahankan bahwa tugas pemeliharaan penting karena melindungi orang yang menggunakan peralatan bersama ketika catatan mendukungnya, daripada menebak motif tersebut hanya dari pertanyaan teknis.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Penalaran + Mesin Artefak

rekonstruksi gerbang penerimaan, keruntuhan, Protokol Manusia, dan rendering penurunan harga atom

**Tanggung jawab.** Mengkoordinasikan jalur rekonstruksi dan rendering yang dibatasi dan memaparkan tanda terima setiap tahap; ini tidak menggantikan penilaian spesialis. Contoh: menjalankan permintaan penulisan melalui seleksi, perencanaan, realisasi, validasi, dan penulisan atom.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Perakitan + Manajer Kemampuan

berjalan mundur dari bidang yang diperlukan, menentukan harga prasyarat, memilih spesialis yang jujur, memesan gelombang ketergantungan, dan melewatkan pekerjaan yang bernilai nol

**Tanggung jawab.** Pilih spesialis mana yang dibutuhkan, urutan pelaksanaannya, dan pekerjaan mana yang tidak memberikan nilai tambah; itu tidak melakukan tugasnya. Contoh: jadwalkan realisasi relasi sebelum realisasi kalimat dan lewati gaya yang tidak tersedia yang tidak memberikan kontribusi apa pun yang diperlukan.

**Harus dilestarikan.** must_preserve_fields; bidang_garis keturunan; eksplisit_tidak tersedianya

**Bentuk sumber daya.** CPU; memori rendah; tidak ada GPU atau sewa

**Batas.** Pengamatan biaya dan nilai memaparkan keputusan namun tidak pernah mendefinisikan kepentingan manusia

### Rekonsiliasi Anggaran Pembawa Atom

mengukur sumber, perekat, dan pembawa hubungan yang tidak dapat dipisahkan sebelum direalisasikan dan mendistribusikan kembali anggaran tetap seluruh produk berdasarkan senjangan bagian asli

**Tanggung jawab.** Periksa apakah fakta dan pembawa hubungan yang tidak dapat dibagi dapat disesuaikan dengan setiap bagian, lalu pindahkan hanya slack yang tersedia sambil mempertahankan total anggaran dokumen. Contoh: memperbesar bagian prosedur 90 kata yang berisi instruksi atom 120 kata yang diperlukan dengan meminjam kata-kata yang tidak terpakai dari bagian lain.

**Harus dilestarikan.** Whole_artifact_budget; pekerjaan_retoris_yang diperlukan; otoritas_sumber; bentuk_grafik

**Bentuk sumber daya.** CPU; waktu proses mendekati nol; mencegah pekerjaan GPU/model/verifier Tahap 8 yang sia-sia

**Batas.** tidak dapat memampatkan proposisi yang tidak dapat dibagi; gagal jika semua operator yang diperlukan melebihi anggaran produk yang dinyatakan

### Manajer Rebinding Terikat Sumber

hanya memindahkan cabang yang terisolasi sepenuhnya ketika tugas produk yang ditetapkan tidak kompatibel dan satu tujuan terbukti kompatibel

**Tanggung Jawab.** Memindahkan cabang bukti yang lengkap dan terisolasi ke satu bagian yang tugasnya dapat menggunakannya secara sah, sambil menolak pemindahan yang ambigu atau mengandung hubungan. Contoh: menetapkan ulang catatan pemulihan mandiri dari penyiapan ke pemecahan masalah tanpa menduplikasinya di kedua bagian.

**Harus dipertahankan.** Branch_identity; sumber_spans; relasi_id; marginal_gain_ledger

**Bentuk sumber daya.** CPU; latensi rendah; tidak ada GPU atau sewa

**Batas.** menolak perpindahan yang mengandung hubungan, ambigu, parsial, atau melebihi kapasitas

### Perwujudan Hubungan Seluruh Dokumen

mengubah sisi penalaran bagian yang sama dan lintas bagian yang diterima menjadi bahasa penghubung yang ringkas dan dapat diputar ulang secara independen tanpa mengulangi kedua operan

**Tanggung jawab.** Mengubah relasi grafik yang diterima menjadi bahasa penghubung yang pendek sekaligus menjaga arah, operan, dan rentang sumber dapat diputar ulang secara independen. Contoh: sadari A-penyebab-B sebagai jembatan sebab-akibat yang terikat, alih-alih mencetak A dan B sebagai fakta-fakta berdekatan yang tidak berhubungan.

**Harus dipertahankan.** relasi_direction; operan_identitas; tepat_carrier_spans; sumber_spans; section_lineage

**Bentuk sumber daya.** CPU; waktu proses mendekati nol; tidak ada GPU atau sewa

**Batas.** hanya merealisasikan jenis relasi yang diterima secara eksplisit; jembatan kompak mempertahankan identitas tepi yang diketik tetapi tetap menggunakan kata-kata mekanis; Sisi pembawa yang sama, ambigu, implisit, dan tidak diketahui tetap terlihat dalam grafik tetapi tidak ditegaskan sebagai prosa

### Mesin Pengetahuan


**Tanggung jawab.** Mengkoordinasikan aksesi, representasi turunan, pencarian, asal usul, dan pekerjaan jangka panjang tanpa menggabungkan tanggung jawab tersebut ke dalam satu keadaan kebenaran. Hal ini memaparkan antarmuka yang didukung kepada konsumen sementara bukti utama tetap dapat ditangani secara independen.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Microplanner Klausa/Kalimat yang Diketik

menugaskan pembawa terikat sumber untuk mengetik pekerjaan retoris dan menyusun rencana klausa, kalimat, dan paragraf

**Tanggung jawab.** Memecah makna dan hubungan yang disetujui menjadi tugas klausa, kalimat, dan paragraf sambil mempertahankan ikatan sumbernya; ia tidak menciptakan kata-kata atau klaim. Contoh: merencanakan klausa penyebab diikuti konsekuensi dan transisinya untuk realisasi permukaan.

**Harus dipertahankan.** semantik_unit_ids; relasi_id; sumber_forms

**Bentuk sumber daya.** CPU; latensi rendah; tidak ada GPU atau sewa

**Batas.** tidak menciptakan proposisi yang hilang atau memperbaiki hubungan yang tidak diklasifikasikan

**Alat publik utama.**[spaCy](https://github.com/explosion/spaCy),[Bling Api](https://github.com/microsoft/BlingFire)

### Manajer Kontrak Produk

mengubah genre, penerima, tujuan, saluran, kebenaran, perhatian, dan anggaran menjadi bidang produk yang dibutuhkan dan karya retoris

**Tanggung jawab.** Ubah permintaan menjadi daftar periksa konkret untuk produk jadi tanpa memilih bukti atau menuliskannya. Contoh: untuk panduan pengguna, memerlukan prasyarat, tindakan yang diperintahkan, panduan pemulihan, dan penutupan sebelum editor dimulai.

**Harus dipertahankan.** dideklarasikan_tujuan; penerima; kebenaran; saluran

**Bentuk sumber daya.** CPU; waktu proses mendekati nol; tidak ada GPU atau sewa

**Batas.** tidak menyimpulkan makna sumber atau memilih fakta

### Kontraktor Permukaan Realizer

menerapkan tata bahasa terbatas, morfologi, tipografi, perspektif, dan transformasi yang diketik ke unit penyampaian

**Tanggung jawab.** Menerapkan tata bahasa, morfologi, tipografi, dan perspektif yang diizinkan pada rencana yang telah disetujui; ia tidak dapat menentukan makna baru. Contoh: mengubah rencana imperatif yang diketik menjadi instruksi tata bahasa tanpa menambahkan klaim keamanan yang tidak pernah diberikan.

**Harus dipertahankan.** Claim_authority; pengikatan_sumber_dan_relasi; pekerjaan_retoris

**Bentuk sumber daya.** CPU; kandidat editor opsional dapat menggunakan sewa GPU yang ada tetapi tidak memiliki otoritas

**Batas.** Tata bahasa tertutup memang sesuai, tetapi gayanya bisa tetap kaku

**Alat publik utama.**[spaCy](https://github.com/explosion/spaCy)

## Manajemen, verifikasi, dan operasi

### Amf Ari


**Tanggung jawab.** Jalankan pengklasifikasi hubungan argumen yang dipasangi pin pada pasangan proposisi yang disediakan dan kembalikan upaya dukungan, konflik, penyusunan ulang, atau tanpa hubungan yang diberi skor. Ia tidak menciptakan proposisi, menyimpulkan motif, atau mengesahkan labelnya sendiri.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[BukaVINO](https://github.com/openvinotoolkit/openvino),[Model AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Pengindeks Obrolan


**Tanggung jawab.** Menyimpan percakapan dalam rekaman panjang dan tidak meninggalkannya di jendela obrolan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Pengindeks File


**Tanggung jawab.** Temukan file yang memenuhi syarat dan kirimkan pekerjaan pengindeksan yang terikat dan mempertahankan asal usulnya. Itu tidak boleh memperlakukan tanggal sistem file, nama file, atau teks yang diekstraksi sebagai waktu, identitas, atau motif pembuatan yang sah.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Telemetri Perangkat Keras


**Tanggung jawab.** Merekam riwayat kondisi mesin yang dibatasi sehingga kegagalan dapat dibandingkan dengan daya, suhu, memori, dan status akselerator. Deskripsi publik menghilangkan irama pengambilan sampel pribadi dan tata letak mesin.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[psutil](https://github.com/giampaolo/psutil)

### Gambar


**Tanggung jawab.** Menghasilkan gambar secara lokal sehingga konsep visual tidak harus melewati batas inferensi eksternal. Pembuatan gambar tetap terpisah dari otoritas bukti dan izin publikasi.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Gambar-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Referensi pengemasan Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Tanggung jawab.** Pikiran yang berat. Lebih lambat dan lebih besar, disimpan untuk pertanyaan yang benar-benar membutuhkan lebih banyak pemikiran daripada kecepatan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Penyematan Ollama


**Tanggung jawab.** Membuat tulisan dapat dicari berdasarkan maknanya, bukan berdasarkan kata-kata yang tepat.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[Ollama](https://github.com/ollama/ollama),[Teks Sematan Nomik](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Sewa Listrik


**Tanggung jawab.** Memungkinkan mesin menganggur dengan tenang dan aktif sepenuhnya untuk pekerjaan nyata.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Judul Ulang Percakapan


**Tanggung jawab.** Memberi nama percakapan yang memiliki arti, sehingga daftarnya dapat ditemukan, bukan hanya berupa kumpulan kalimat pertama.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Pengamat Semantik


**Tanggung jawab.** Memeriksa apakah suatu jawaban didukung oleh materi yang diklaim berasal darinya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[transformator](https://github.com/huggingface/transformers),[Periksa Mini](https://github.com/Liyan06/MiniCheck),[FaktaCG](https://github.com/derenlei/FactCG)

### Analisis Kemiringan


**Tanggung jawab.** Menyimpan catatan bagaimana setiap pikiran gagal dan apakah itu menjadi lebih baik atau lebih buruk.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[spaCy](https://github.com/explosion/spaCy),[Bling Api](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Pidato


**Tanggung jawab.** Mengubah ucapan menjadi teks, jadi berbicara adalah salah satu cara untuk menuliskan sesuatu.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[Pidato](https://github.com/speaches-ai/speaches),[bisikan lebih cepat](https://github.com/SYSTRAN/faster-whisper),[lebih cepat-distilasi-bisikan-besar-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Layanan Tugas


**Tanggung jawab.** Baca catatan tugas resmi sebagai bukti tentang pekerjaan yang direncanakan tanpa mengubahnya menjadi pengingat, kesimpulan motif, atau kebenaran korpus.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### vLLM


**Tanggung jawab.** Pikiran sehari-hari. Cepat, selalu dimuat, menjawab hampir semuanya.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

**Alat publik utama.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Pekerjaan Panggung yang Tahan Lama

batch terbatas, pos pemeriksaan, pembatalan, resume, dan kegagalan sebagian

**Tanggung jawab.** Jalankan tahapan artefak yang panjang sebagai tugas terbatas yang dapat dilanjutkan dengan status terminal yang benar, alih-alih mengikatnya ke satu permintaan browser. Contoh: melanjutkan setelah pos pemeriksaan promosi terverifikasi daripada mengulangi alasan yang mahal setelah gangguan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Eksekusi + Manajer Manifes

menjalankan adaptor yang ditugaskan dan mencatat metode fisik, titik akhir, revisi model, hash, tepi panggilan, waktu, percobaan ulang, dan disposisi

**Tanggung jawab.** Jalankan setiap spesialis yang ditugaskan dan catat apa yang dieksekusi secara fisik, beserta masukan, identitas, waktu, percobaan ulang, dan hasilnya. Contoh: menunjukkan bahwa pengklasifikasi AMF yang dipasangi pin menangani Tahap 2 alih-alih memercayai label manifes yang hanya menyatakan demikian.

**Harus dipertahankan.** input_hashes; identitas_adaptor; kegagalan_status

**Bentuk sumber daya.** Koordinator CPU; mendelegasikan pekerjaan GPU hanya melalui pemilik sewa yang dinyatakan

**Batas.** mencatat eksekusi; tidak dapat mensertifikasi keberhasilannya sendiri

### Arbitrase Sewa GPU


**Tanggung jawab.** Mengkoordinasikan penyerahan saran antara beban kerja akselerator yang dikelola platform tanpa memperlihatkan identitas perangkat fisik atau mendahului pekerjaan yang sudah dalam penerbangan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Koordinator Power Residensi

**Tanggung jawab.** Mempertahankan satu model status ACTIVE, WARM, IDLE, dan NEVER di seluruh mekanisme kekuatan dan residensi platform terdistribusi.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

### Buku Besar Muatan yang Diharapkan/Diamati

menggabungkan setiap tanggung jawab roda gigi ke bidang yang diamati, kesiapan, kelalaian, nilai, biaya, waktu, percobaan ulang, dan permintaan perbaikan

**Tanggung jawab.** Bandingkan kontribusi yang diharapkan dari setiap roda dengan kontribusi yang sebenarnya diberikan, termasuk biaya dan masukan yang hilang. Contoh: memperlihatkan bahwa analisis relasi berjalan selama 40 detik tetapi tidak memberikan keunggulan penghubung yang dapat digunakan kepada editor.

**Harus dipertahankan.** handoff_identity; mencerna; bidang_hilang; dasar_biaya

**Bentuk sumber daya.** CPU; mendekati nol dibandingkan dengan penalaran dan verifikasi

**Batas.** pewaktuan bagian portabel tidak menggantikan pewaktuan tahap/model fisik dalam manifes eksekusi

### Manajer Kualitas Sadar Produk

memeriksa penyelesaian retoris, penalaran penghubung, keterbacaan, tipografi, duplikasi, perhatian, anggaran, tenunan, slop, dan tindakan yang dapat dieksekusi untuk produk yang diminta

**Tanggung jawab.** Evaluasi apakah produk khusus ini berfungsi sesuai pembaca dan tujuan yang dinyatakan di seluruh sumbu kualitas yang berbeda, lalu identifikasi tahap perbaikan yang bertanggung jawab. Contoh: sebuah manual bisa gagal jika tidak ada panduan pemulihan meskipun setiap kalimat memiliki tata bahasa dan membumi.

**Harus dipertahankan.** individual_axis_results; bukti_kandidat_ditolak

**Bentuk sumber daya.** CPU ditambah pemverifikasi terbatas/penghapusan HTTP; secara historis merupakan pangsa Tahap 8 terbesar

**Batas.** sumbu genre harus diukur dan dibuat versinya; satu skor kualitas buram dilarang

### Tanda Terima + Manajer Promosi

secara independen menghitung ulang invarian dan mengizinkan penulisan promosi dan artefak atom hanya dari tanda terima PASS

**Tanggung jawab.** Verifikasi bundel secara independen dan tulis artefak hanya setelah setiap invarian yang diperlukan lolos. Contoh: menolak promosi ketika penyaji melaporkan keberhasilan tetapi tanda terimanya tidak dapat mereproduksi pengikatan sumber.

**Harus dipertahankan.** fail_results; tidak diketahui; rilis_identitas; rollback_boundary

**Bentuk sumber daya.** CPU dan I/O; tidak ada GPU atau sewa

**Batas.** Keaslian manifes pada akhirnya bergantung pada pengikatan rilis/konfigurasi yang tidak dapat diubah dan ditinjau

### Asal + Kontrol Kerugian

identitas sumber, keadaan epistemik, inferensi, penemuan, dan cabang yang ditolak

**Tanggung jawab.** Jaga agar setiap pernyataan selalu dikaitkan dengan siapa atau apa yang memberikan pernyataan tersebut, kapan pernyataan tersebut diterapkan, dan apakah pernyataan tersebut dipatuhi, disimpulkan, digantikan, ditolak, atau tidak diketahui. Contoh: pertahankan interpretasi ulang di kemudian hari tanpa menimpa keyakinan sebelumnya yang sebenarnya memandu suatu tindakan.

**Harus dipertahankan.** Identitas grafik yang tepat, asal hubungan, dan batas komponen yang dinyatakan.

**Bentuk sumber daya.** Penerapan langsung mencatat penggunaan CPU, memori, penyimpanan, akselerator, dan sewa aktual; katalog publik ini tidak memaparkan penempatan mesin.

**Batas.** Hanya dapat menjalankan tanggung jawab grafik yang dinyatakan dan tidak dapat memperbaiki bukti hulu yang hilang atau tidak didukung.

## Komponen tambahan yang dideklarasikan

### Gerbang Web Aman

Memberikan akses jarak jauh yang terautentikasi dari klien yang disetujui tanpa secara langsung memaparkan layanan platform pribadi ke internet publik.

### Pengawas Platform

Memulai layanan dalam urutan ketergantungan, mengamati kesehatannya, dan melakukan tindakan restart terbatas. Kegagalannya menghilangkan pengawasan yang terkoordinasi tanpa mendefinisikan kembali kondisi layanan yang masih berjalan.

## Batas kelengkapan

Katalog mencakup komponen logis aktif dalam grafik arsitektur yang dikelola, tidak setiap paket transitif yang diinstal pada setiap runtime. Rilis perangkat lunak di masa depan memerlukan tagihan bahan perangkat lunak dan bundel lisensi yang tepat yang dihasilkan dari byte tertentu yang didistribusikan.
