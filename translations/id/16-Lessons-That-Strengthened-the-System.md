> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Pelajaran yang Memperkuat Sistem

## Mengapa perilaku termasuk dalam arsitektur

Setiap bug dapat diperbaiki sementara pola yang menyebabkannya tetap ada. Oleh karena itu, catatan ini menghubungkan pola rekayasa yang berulang dengan kemungkinan pendorongnya, dampaknya terhadap manusia dan bukti, serta mekanisme yang mendukung hasil yang lebih andal.

Pengamatan asli muncul selama pengembangan swasta. Akun publik ini menyimpan pelajaran teknik yang dapat ditransfer sambil menghapus kutipan pribadi, identitas, irama, dan keadaan. Itu tidak mendiagnosis orang atau sistem mana pun. Setiap pola menggambarkan perilaku yang dapat diamati dan koreksi desain yang sesuai.

## Pola kerja dan keputusan

### Mengintegrasikan materi baru dengan hati-hati

Materi baru dibaut ke dokumen atau komponen yang sudah ada tanpa memahami strukturnya. Baik penambahan maupun pembawa acara menjadi lebih sulit untuk dipahami.

**Koreksi:** membaca struktur penerima, mengintegrasikan tanggung jawab baru sesuai prasyarat dan konsumennya, atau memberinya komponen terikat terpisah.

### Menjaga otoritas dalam ruang lingkup

Tindakan yang berdekatan dianggap sebagai izin tersirat. Sistem mengubah lebih dari permintaan yang diotorisasi.

**Koreksi:** menjaga cakupan wewenang sesuai dengan hasil yang diminta. Mutasi yang berbeda secara material memerlukan keputusan baru.

### Bukti sebelum selesai

“Diubah” atau “dijalankan” dilaporkan sebagai “berhasil”, dan pernyataan bahwa peraturan dipatuhi merupakan bukti bahwa peraturan tersebut telah diterapkan.

**Koreksi:** mengikat penyelesaian ke prasyarat yang dapat diamati, eksekusi, hasil, pengujian regresi, dan identitas artefak yang tepat. Laporan mandiri tidak memiliki otoritas rilis.

### Diagnosis kausal yang cermat

Diagnosis yang dapat diandalkan dimulai dengan perubahan lokal terkini, data dasar, hipotesis yang bersaing, dan reproduksi sebab akibat sebelum tanggung jawab diberikan kepada komponen mana pun.

**Koreksi:** membedakan korelasi, perubahan kondisi, reproduksi, dan mekanisme yang dikonfirmasi. Periksa perubahan terbaru dalam cakupan terlebih dahulu.

### Interpretasi berdasarkan sumber

Pesan kesalahan, baris log, atau penjelasan yang masuk akal diterima tanpa memeriksa sumber, keadaan, waktu, atau kemampuan untuk menjelaskan hasil yang diamati.

**Koreksi:** mempertahankan asal dan status tidak diketahui. Persempit pertanyaan yang belum terjawab alih-alih mengisinya dengan penyebab yang masuk akal.

### Koreksi terbatas dan rilis stabil

Koreksi yang valid dilakukan melewati targetnya, atau karya berulang kali direvisi di depan umum sebelum desainnya stabil. Keduanya memberikan perhatian dan menciptakan regresi.

**Koreksi:** tentukan negara bagian yang akan digunakan, gunakan pengujian kecil yang dapat diperiksa, dan perubahan tervalidasi yang kompatibel secara batch sebelum dirilis.

### Mempertahankan jalur pembelajaran

Mencatat masalah dan dampaknya sebelum perbaikan akan melestarikan pembelajaran yang memungkinkan perbaikan.

**Koreksi:** catat kegagalan dan dampaknya sebelum perbaikan. Koreksi ini lebih berguna bila alasannya tetap terlihat.

## Arsitektur dan pola integrasi

### Kecerdasan yang dibangun dengan tujuan

Perintah chatbot umum menggantikan mekanisme khusus karena model tersebut tampaknya mampu mengimprovisasi pekerjaan yang hilang.

**Koreksi:** menentukan semantik input, output, otoritas, biaya, dan kegagalan yang hilang; mengevaluasi spesialis nyata atau mekanisme deterministik; jaga agar jalur tidak tersedia sampai jalur itu ada.

### Nilai dari sumber resmi

Konstanta atau default mewakili fakta yang sudah diketahui oleh sumber resmi. Ini berfungsi untuk spesimen saat ini dan diam-diam gagal ketika dunia berubah.

**Koreksi:** menyelesaikan nilai dari pemiliknya. Jika tidak ada sumber, tampilkan yang tidak diketahui atau tidak tersedia daripada membuat default.

### Peran dan otoritas yang berbeda

Pengamat, calon generator, trafo, verifikator, veto, penyaji, dan gerbang pelepasan diperlakukan sebagai sesuatu yang dapat dipertukarkan karena masing-masing tampak “memeriksa” sesuatu.

**Koreksi:** setiap roda menyatakan tanggung jawabnya, konsumen, otoritas, status siklus hidup, batasan, dan hubungan penggantian.

### Evolusi yang sadar konsumen

Suatu komponen disebut usang karena pemanggilnya saat ini tidak menggunakannya, sedangkan konsumen hilir yang dituju atau produk masa depan masih bergantung pada kemampuannya.

**Koreksi:** melacak konsumen yang dituju saat ini dan terdokumentasi sebelum penghapusan. Klasifikasikan komponen menjadi aktif, belum selesai, diganti, ditolak, dipertahankan, atau tidak dapat dijelaskan.

### Menghormati tujuan yang dipilih

Ketika tujuan yang dikonfigurasi tidak dapat dicapai, output secara diam-diam dipindahkan ke tempat yang lebih mudah daripada memperbaiki akses. Organisasi dan harapan sebelumnya hilang.

**Koreksi:** memperlakukan tujuan yang dikonfigurasi sebagai pekerjaan pengguna yang telah dilakukan. Perbaiki akses atau minta keputusan relokasi yang eksplisit.

### Verifikasi di batas operasi

Pengujian lolos dengan identitas yang memiliki akses lebih banyak daripada komponen produksi.

**Koreksi:** verifikasi berdasarkan batas identitas dan sumber daya yang dijalankan, atau beri label pada hasil yang tidak terbukti.

### Klaim cocok dengan amplop tes mereka

Kasus tiruan, perlengkapan unit, jangka pendek, atau berurutan disajikan sebagai bukti untuk jalur konkuren langsung dengan model, batch, izin, dan sumber daya yang berbeda.

**Koreksi:** setiap hasil memberi nama pada amplopnya. Skalakan hanya setelah batas-batas kecil dan menengah disahkan, dan jangan pernah memperluas klaim secara diam-diam.

### Koordinasi sejarah bersama yang dapat diatribusikan

Beberapa pekerja menulis ulang satu dokumen status yang tampak kanonik. Pekerjaan bisa hilang selama file masih tampil terkini.

**Koreksi:** mempertahankan rekaman aliran kerja yang tidak dapat diubah dan diatribusikan serta mendapatkan tampilan terkini dari rekaman tersebut.

### Keadaan sadar waktu

Keadaan saat ini, sejarah, percobaan, karantina, penolakan, dan digantikan ditulis sebagai fakta yang tak lekang oleh waktu.

**Koreksi:** lampirkan siklus proses dan status validitas pada setiap observasi material.

## Pola keluaran dan perhatian

### Mempertahankan sinyal manusia

Catatan singkat manusia diperluas dengan materi yang dihasilkan hingga peristiwa aslinya sulit dipulihkan.

**Koreksi:** simpan ucapan atau artefak sebagai catatan. Konteks yang dihasilkan adalah lapisan turunan terpisah dengan otoritas eksplisit.

### Keluaran yang lengkap dan ringkas

Suatu jawaban dijelaskan, dirangkum, dinyatakan kembali, dan disimpulkan setelah informasinya habis.

**Koreksi:** berhenti ketika informasi yang diminta telah terkirim. Struktur harus sesuai dengan karya pembaca yang berbeda.

### Menghargai perhatian pembaca

Detail yang benar namun tidak diminta hanya menghabiskan perhatian pembaca yang terbatas. Penulis memulai biaya itu.

**Koreksi:** menganggap perhatian sebagai sumber daya. Simpan detail opsional di balik kontrol perluasan dan biarkan pembaca memulai transaksi.

### Penekanan yang bermakna

Semuanya ditandai penting, sehingga sinyal bermakna menjadi tidak bisa dibedakan dari dekorasi.

**Koreksi:** memperlakukan judul, teks tebal, tabel, peringatan, dan peringatan berulang sebagai anggaran sinyal yang terbatas.

### Memimpin dengan jawabannya

Konten yang bermanfaat ada tetapi disimpan dalam volume yang tidak diminta oleh pembaca. Pembaca membayar biaya ekstraksi.

**Koreksi:** memimpin dengan hasil yang diminta, menghapus material bernilai rendah, dan menawarkan perluasan yang dapat dilacak daripada memaksakan konsumsi.

### Antarmuka yang stabil dan ketersediaan yang jujur

Pembaruan langsung harus mempertahankan pilihan, fokus, gulir, dan penyalinan sementara pengukuran bersumber menunjukkan apa yang benar-benar tersedia.

**Koreksi:** menambal nilai aktif pada tempatnya, mempertahankan status pengguna, menampilkan pengukuran bersumber, dan menjaga agar tidak tersedia tetap ringkas dan eksplisit.

## Penyebab yang menghubungkan

![Jalur yang gagal dilestarikan dan diubah menjadi perbaikan arsitektur yang terverifikasi](../../assets/failures-became-blueprint.png)

### Transfer korpus yang didorong oleh kenyamanan

Komponen eksternal yang kuat diberikan pada korpus yang terpelihara karena ia juga dapat melakukan satu tugas hilir yang sempit. Penyerahan ini memperluas kontribusi yang dapat diganti ke dalam penyimpanan yang tidak perlu atas aset pengetahuan yang tahan lama, sehingga memungkinkan ekstraksi dan pengurangan destruktif yang menjadi sandaran keuntungan institusional terpusat.

**Koreksi:** membuat payload kerja resmi terkecil yang mendukung operasi yang dinyatakan. Jaga korpus, asal usul, keadaan waktu, dan mekanisme rekonstruksi di masa depan di belakang batas lokal. Desainnya harus tetap bagus meskipun penerimanya masih menyimpan muatannya, karena keadaan yang dihilangkan membawa makna kemanusiaan dan nilai gabungan di bawah kendali manusia.

Tiga penyebab berulang pada perilaku ini:

1. mengaitkan kemajuan dengan efek yang terverifikasi;
2. melestarikan perbedaan yang membawa otoritas, waktu, keamanan, atau makna;
3. mengubah akomodasi sementara menjadi keputusan eksplisit dan arsitektur yang tahan lama.

Respons yang tahan lama bukanlah instruksi yang lebih panjang. Ini adalah kontrak yang diketik, penyerahan yang dapat diamati, gerbang independen, dan kasus regresi yang melekat pada perilaku yang penting.
