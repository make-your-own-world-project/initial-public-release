> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Menjaga Penalaran Tetap Dapat Diperiksa

![Spesialis independen menelusuri jalur penalaran yang diterima dan ditolak hingga ke bukti yang tepat](../../assets/reasoning-engine-inspectable-path.png)

## Alasan yang bisa diperiksa

Mesin penalaran adalah serangkaian spesialis yang dibatasi dan proyeksi deterministik. Tujuannya adalah untuk membangun grafik proposisi dan hubungan yang dapat diperiksa dari bukti sumber yang tepat. Ini bukan perintah penyelesaian umum yang diminta untuk menyimpulkan keseluruhan dokumen.

```text
EXACT EVIDENCE ITEMS AND SOURCE SPANS
        |
DISCOURSE AND REFERENCE PREPROCESSING
        |
PROPOSITION AND RELATION CANDIDATES
        |
ARGUMENT RELATION CLASSIFICATION
        |
TYPED PROVENANCE GRAPH
        |
DETERMINISTIC DEPENDENCY AND WHY PROJECTION
        |
PRODUCT-SPECIFIC SELECTION AND RECONSTRUCTION
        |
INDEPENDENT VERIFIER AND RECEIPT
```

## Pemrosesan awal linguistik

Bukti dibagi menjadi potongan-potongan yang dibatasi dan tanpa celah yang diikatkan pada identitas sumber yang tidak dapat diubah dan penyeimbangan karakter. Analisis coreference mengusulkan rantai referensi. Analisis Teori Struktur Retoris mengusulkan struktur wacana dan pasangan operan. Struktur yang terlalu besar atau tidak terikat tetap terlihat eksplisit dibandingkan dipotong secara diam-diam atau dipetakan ke frasa pertama yang cocok.

Alat-alat ini memaparkan struktur linguistik. Mereka tidak menetapkan motif pribadi atau kebenaran argumen dengan sendirinya.

## Klasifikasi relasi argumen

Pasangan proposisi turunan wacana diklasifikasikan ke dalam inventaris relasi kecil, termasuk dukungan, konflik, kesetaraan, atau tidak ada relasi otoritatif. Setiap upaya mempertahankan operan, distribusi skor, identitas model, dan disposisinya. Hasil di bawah ambang batas tetap terlihat dan tidak menimbulkan tepian.

Relasi yang diterima menjadi tepi grafik berarah dengan rentang sumber dan identitas metode yang tepat. Pengikatan sumber yang ambigu gagal ditutup.

## Proyeksi grafik

Pandangan ketergantungan dan “mengapa” adalah proyeksi deterministik dari tepi yang sudah diklasifikasikan. Hal ini dapat mengungkap rantai dukungan atau konflik dalam bentuk yang lebih bermanfaat. Ia tidak boleh menciptakan alasan, pertaruhan, atau konsekuensi baru dan menyatakan bahwa seorang spesialislah yang menentukan alasan, risiko, atau konsekuensi tersebut.

Grafik dapat diekspor melalui struktur pertukaran argumen yang sudah ada, namun representasi pertukaran bukanlah penyimpan kebenaran kedua dan tidak memerlukan model atau akselerator.

## Batasan sumber daya

Penguraian inti dan wacana dapat menggunakan kapasitas akselerator yang disewakan karena model tersebut dimuat untuk pekerjaan prapemrosesan yang dibatasi. Klasifikasi argumen dirancang untuk dijalankan melalui jalur inferensi spesialis yang ringkas. Proyeksi grafik, pemilihan, penyelesaian kendala, pemeriksaan asal, dan verifikasi penerimaan adalah pekerjaan CPU biasa.

Desainnya menghindari setiap model tetap tinggal dan melarang memulai pekerja duplikat untuk menghindari mekanisme sewa bersama.

## Apa yang dibuktikan dan tidak dibuktikan oleh pemeriksa

Pemverifikasi dapat membuktikan bahwa komponen yang diperlukan berjalan, rentang yang tepat bertahan, proyeksi grafik dapat direproduksi, pengikatan produk konsisten, dan byte yang dipromosikan cocok dengan paket yang diterima. Ia dapat menolak manifes yang dibuat-buat, prosa yang tidak didukung, arah yang salah, kemunduran yang tersembunyi, dan hilangnya kemampuan dalam kebijakannya.

Kebenaran struktural tidak secara otomatis membuktikan bahwa setiap label relasi sesuai dengan penilaian ahli manusia. Evaluasi kualitas hubungan memerlukan contoh yang diberi label secara independen dan analisis presisi, penarikan kembali, pengarahan, dan kalibrasi. Gerbang kualitas semantik itu tetap menjadi tanggung jawab tersendiri.

Batasan ini juga menghalangi model eksternal hilir untuk menjadi otoritas penalaran. Ia mungkin menerima proposisi yang didukung dan hubungan yang diketik untuk tugas realisasi yang dibatasi, sementara bukti, upaya, grafik, dan kriteria penerimaan tetap tersedia secara independen. Kefasihan tidak mengambil kepemilikan atas alasan yang membuat muatan tersebut berguna.
