> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Apa yang Nyata dan Apa yang Tersisa

![Ide, pengujian, kegagalan, dan kemampuan terverifikasi melintasi gerbang implementasi yang berbeda](../../assets/evidence-implementation-gates.png)

## Kelas bukti

Model bukti membedakan beberapa kelas:

- **bukti utama:** artefak sumber dan peristiwa interaksi yang diawetkan;
- **bukti yang diperoleh:** teks yang diekstraksi, unit semantik, hubungan, klasifikasi,
  observasi temporal, dan representasi versi lainnya;
- **bukti eksekusi:** manifes, observasi panggilan, biaya, identitas model, dan
  hasil tahapan;
- **bukti penerimaan:** invarian independen, tanda terima, paket yang dipromosikan, dan
  hash keluaran yang tepat;
- **maksud desain:** arsitektur dan perilaku yang direncanakan belum terbukti dalam pelaksanaan;
- **klaim historis:** apa yang dilaporkan oleh rilis atau eksperimen sebelumnya.

Tes kelulusan hanyalah bukti untuk amplop yang dimilikinya. Dokumen rilis bukanlah bukti bahwa runtime saat ini masih cocok dengan itu. Perpustakaan yang terinstal bukanlah kemampuan yang disebarkan.

## Fondasi yang diterapkan

Implementasinya telah menunjukkan landasan yang terikat sebagai berikut:

- pelestarian sumber yang ditujukan pada konten dan penanganan bukti yang berorientasi pada lampiran;
- memisahkan artefak, representasi, pencari lokasi, dan sumber peristiwa;
- peristiwa percakapan yang terikat pada aktor dan urutan;
- pemrosesan awal wacana dan intireferensi dengan potongan sumber terbatas;
- klasifikasi relasi argumen dengan rentang sumber yang tepat dan upaya yang dipertahankan;
- grafik proposisi dan relasi yang diketik;
- proyeksi ketergantungan deterministik;
- kontribusi Matriks Makna Pribadi cakupan permintaan dengan ketidakpastian dan
  bendera perlindungan;
- pemilihan mundur dan objek pemutaran ulang maju dengan grafik yang sama dalam pengujian terbatas;
- alokasi unit semantik yang dimiliki secara global dan perencanaan artefak yang saling terkait;
- lantai rendering yang membumi dan perbandingan kandidat opsional;
- promosi mandiri dengan gerbang penerimaan;
- pekerjaan artefak yang tahan lama dan penampil penalaran;
- batasan publikasi dokumen publik dengan rilis yang ditujukan pada konten.

Pernyataan-pernyataan ini menggambarkan batasan-batasan komponen yang ditunjukkan, bukan klaim bahwa keseluruhan visi sudah lengkap.

Perbandingan yang ditunjukkan juga mencatat batas roda gigi eksternal. Model frontier menerima muatan khusus permintaan yang telah disiapkan dan memberikan kontribusi rendering yang lebih halus tanpa menerima korpus yang dipelihara atau menjadi otoritas rilis. Bukti yang mendukung transaksi terikat itu; hal ini tidak menetapkan apa yang disimpan oleh penyedia mana pun di luar jalur artefak yang diuji, yang tetap menjadi pertanyaan kontrak dan privasi terpisah. Hal ini menetapkan bahwa kontribusi yang bermanfaat tidak memerlukan pengalihan catatan manusia untuk pengurangan destruktif menjadi nilai milik penyedia.

## Skala platform terpasang

Inventaris sistem file terbatas dari pohon aplikasi yang diinstal berjumlah sekitar 566.000 file dan 218 GiB. Aset model menyumbang sekitar 172 GiB, dependensi dan waktu proses bahasa sebesar 25 GiB, status data dan aset lainnya sebesar 20 GiB, dan sumber implementasi sekitar 184 MiB. Inventaris menemukan beberapa entri yang tidak dapat dibaca atau berubah, sehingga ini merupakan perkiraan skala operasional dan bukan tagihan material perangkat lunak.

Asimetri adalah bukti yang disengaja tentang arsitektur. Kode sumber adalah bagian kecil dari tapak yang terpasang; bobot model dan runtime yang dapat digunakan kembali mendominasinya. Oleh karena itu, bidang kendali melacak nilai, wewenang, dan biaya pengoperasian setiap spesialis daripada memperlakukan ukuran terpasang sebagai kemampuan. Rilis kode yang dapat didistribusikan di masa mendatang memerlukan inventaris ketergantungan khusus artefak, versi yang tepat, lisensi, hash, dan batasan build yang dapat direproduksi.

## Pelajaran teknik dilestarikan oleh desain

Pembangunan menghasilkan beberapa pelajaran teknik yang tahan lama:

- mendorong model umum untuk mensimulasikan spesialis yang hilang;
- memperlakukan proses keluar atau manifes yang dilaporkan sendiri sebagai bukti kemampuan;
- menjalankan wacana setelah klasifikasi semantik dan menduplikasi karya spesialis;
- menetapkan kemunculan kutipan berulang pertama sebagai asal;
- mengizinkan satu item bukti seluruh file membuat komposisi tidak dapat diverifikasi;
- memperlakukan hubungan yang tidak diterima sebagai kegagalan saluran pipa;
- membingungkan proyeksi grafik deterministik dengan spesialis yang dieksekusi secara terpisah;
- mencocokkan profil tenunan sambil menghasilkan prosa yang tidak didukung atau tidak dapat dibaca;
- debugging dengan seluruh korpus berjalan ketika kasus kecil dan menengah memperlihatkan cacat;
- menyetel satu produk sedemikian rupa sehingga dapat menurunkan produk lainnya.

Arsitektur publik mempertahankan koreksi ini karena dapat menjelaskan tujuan dari kendala saat ini dan membuat perbaikan di masa depan lebih dapat diandalkan.

## Peluang pengembangan saat ini

Beberapa kemampuan utama masih belum lengkap atau memerlukan bukti yang lebih luas:

- label relasi memerlukan evaluasi kualitas ahli yang independen, tidak hanya struktural
  validasi;
- tautan temporal simpanan silang dan reatribusi memerlukan pengujian lanjutan dalam skala yang lebih besar
  batas-batas sumber campuran;
- pengemudi pribadi tingkat tinggi harus tetap tidak berpenghuni sampai ada bukti yang jelas dan
  perilaku lensa membenarkannya;
- jenis produk yang berbeda memerlukan jalur perakitan yang terkalibrasi dan dilindungi regresi;
- Umpan balik dari Protokol Manusia memerlukan bukti hasil jangka panjang;
- mekanisme figuratif dan naratif memerlukan evaluasi kesadaran produk sebelumnya
  wewenang diberikan;
- dokumentasi publik yang lengkap memerlukan tinjauan editorial lanjutan sebagai catatan pribadi
  berkembang.

## Tangga validasi

Perkembangan berlangsung dari kecil ke besar:

1. skema murni dan perlengkapan invarian;
2. contoh semantik singkat dengan topologi yang diketahui;
3. irisan kecil sumber nyata;
4. irisan format campuran sedang dan waktu campuran;
5. batas skalabilitas yang lebih besar setelah level sebelumnya dilewati;
6. perbandingan yang dibuat oleh manusia versus yang dibuat oleh sistem berdasarkan bukti yang sama,
  penerima, bentuk, dan anggaran.

Perbandingan tersebut mendiagnosis apakah kerugian berasal dari pemilihan grafik, alokasi kepentingan, pemutaran ulang ke depan, realisasi, atau keterbacaan akhir, alih-alih menetapkan setiap cacat pada “kualitas model” umum.
