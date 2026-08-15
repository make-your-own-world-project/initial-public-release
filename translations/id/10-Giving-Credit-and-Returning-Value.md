> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Memberi Kredit dan Mengembalikan Nilai

![Jalur pengetahuan yang diatribusikan mengembalikan peta publik yang berguna tanpa menghapus sumbernya](../../assets/publish-reciprocity-open-paths.png)

Sistem ini dirakit secara independen dari sebagian besar perangkat keras bekas, sumber daya pribadi, dan upaya besar di luar lapangan kerja. Landasan intelektualnya berasal dari orang-orang dan institusi yang bersedia menerbitkan karya yang dapat diperiksa, diuji, diadaptasi oleh pihak lain, dikritik, dan dikembangkan sesuai dengan ketentuannya. Oleh karena itu, atribusi mencatat silsilah teknis dan kewajiban timbal balik: pekerjaan umum membuat karya tersebut menjadi mungkin, dan edisi publik mengembalikan temuan-temuan terbatasnya tanpa mengklaim kepemilikan atas konteks yang menghasilkannya.

## Mengapa buku besar ini ada

Karya ini tidak akan ada tanpa orang-orang yang memilih untuk mempublikasikan penelitian, menulis dan memelihara perangkat lunak, melestarikan karya budaya, menerjemahkan teks, mengkurasi corpora, mengoperasikan arsip, dan membuat karya mereka tersedia untuk digunakan kembali atau dipelajari. Keputusan mereka untuk berbagi merupakan perwujudan kedaulatan. Ketersediaan publik tidak menjadikan kontribusi mereka anonim atau tanpa pemilik.

Buku besar mencatat kontribusi utama yang digunakan dalam arsitektur publik. Ini menyatakan apa yang disediakan oleh setiap sumber, bagaimana sumber tersebut digunakan, dan hubungan antara sumber dan proyek ini. Kategori-kategori itu penting:

- **ketergantungan aktif** berarti perangkat lunak atau model dijalankan di jalur saat ini;
- **metode yang diadaptasi** berarti implementasi menggunakan mekanisme yang dipublikasikan tanpa
  mengklaim kode asli sebagai pembuat proyek;
- **sumber kalibrasi** berarti materi diukur, tidak direproduksi di depan umum
  melepaskan;
- **pengaruh desain** berarti karya tersebut mengubah keputusan arsitektur;
- **dievaluasi atau ditolak** mempertahankan kredit dan hasil eksperimen tanpa
  menyiratkan adopsi.

Tidak ada entri yang menyiratkan bahwa penulis, pengelola, komunitas, penerbit, arsip, atau lembaga mendukung proyek ini. ZIP dokumentasi ini tidak mendistribusikan ulang kode, bobot model, teks kumpulan data, atau teks artikelnya.

## Landasan sastra, linguistik, dan komunikasi

| Kontribusi | Sumber publik atau karya identifikasi | Apa kontribusinya di sini | Hubungan |
|---|---|---|---|
| Carlota S.Smith | *Cara Wacana: Struktur Lokal Teks* | Perbedaan tata bahasa di antara cara-cara wacana; mendukung analisis pengiriman yang diketik. | Pengaruh desain |
| M.A.K. Halliday dan Ruqaiya Hasan | *Kohesi dalam bahasa Inggris* | Memisahkan kohesi permukaan dari koherensi sebenarnya. | Pengaruh desain dan dasar pengukuran |
| M.A.K. Halliday | Daftarkan sebagai bidang, tenor, dan mode | Memperlakukan audiens dan situasi komunikatif sebagai dimensi yang terukur dan bukan sekadar hiasan. | Pengaruh desain |
| Douglas Biber | *Variasi dalam Ucapan dan Tulisan* | Analisis register multidimensi menggunakan fitur-fitur yang dapat diamati secara bersamaan. | Garis keturunan pengukuran tenun |
| William Mann dan Sandra Thompson | Teori Struktur Retoris | Hubungan wacana, inti, dan pembedaan antara materi sentral dan materi pendukung. | Silsilah spesialis aktif |
| John Swales | *Analisis Genre* | Gerakan dan langkah retoris yang digunakan untuk menggambarkan struktur produk. | Silsilah kontrak produk |
| Gérard Genette dan tradisi Formalis Rusia | *Wacana Narasi*; fabula dan sjuzhet | Memisahkan materi peristiwa dari urutan dan sudut pandang penceritaannya. | Pengaruh naratif dan rekonstruksi |
| H.P.Grice | “Logika dan Percakapan” | Maksim kooperatif dan perbedaan antara pelanggaran yang disengaja dan pelanggaran yang tidak disengaja. | Protokol Manusia dan desain detektor |
| Douglas Walton | Skema argumentasi dan pertanyaan kritis | Memberikan pola tantangan yang dapat diperiksa, bukan hanya satu skor argumen yang tidak jelas. | Pengaruh analisis argumen |
| Alexandra Aihenvald | *Bukti* | Memperlakukan penandaan sumber dan bukti sebagai tanggung jawab linguistik. | Pengaruh peran epistemik |
| Claude Shannon | “Teori Komunikasi Matematika” | Menyediakan kosakata komunikasi formal untuk informasi, batasan saluran, redundansi, dan kehilangan. | Pengaruh arsitektur komunikasi |
| Herbert Clark dan Susan Haviland | Diberikan kontrak baru | Mendukung pengukuran apa yang diasumsikan diketahui oleh penerima dan apa yang harus diperkenalkan. | Garis keturunan pengukuran tenun |
| Morton Ann Gernsbacher | Kerangka pembangunan struktur | Mendukung pembentukan, pemetaan, dan analisis koherensi yang berorientasi pada penerima. | Pengaruh Protokol Manusia |
| Benyamin Bloom; Lorin Anderson dan David Krathwohl | Taksonomi tujuan pendidikan | Menyediakan kosakata yang dibatasi secara eksplisit untuk kedalaman penerima yang diharapkan. | Pengaruh kontrak audiens |

Karya-karya ini memberikan metode dan pertanyaan, bukan jawaban universal tentang seseorang. Kontribusi arsitekturalnya adalah untuk menghubungkan mekanisme terbatasnya ke jalur perakitan yang melestarikan asal usulnya dan menjaga setiap kesimpulan dapat dibalik dan diperiksa.

## Seleksi, pengeditan, dan realisasi

| Kontribusi | Sumber publik | Apa kontribusinya di sini | Hubungan |
|---|---|---|---|
| Jaime Carbonell dan Jade Goldstein | “Penggunaan MMR, Pemeringkatan Berbasis Keberagaman untuk Menyusun Ulang Dokumen dan Memproduksi Ringkasan” | Menyeimbangkan relevansi dan kebaruan selama seleksi terbatas. | Metode yang disesuaikan |
| Hui Lin dan Jeff Bilmes | Peringkasan submodular di bawah anggaran | Seleksi hasil yang semakin berkurang di bawah anggaran yang jelas. | Metode yang disesuaikan |
| Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka, dan Aliaksei Severyn | penanda laser | Mendemonstrasikan pengeditan terbatas dengan kosakata penyisipan tertutup. | Pengaruh desain yang dievaluasi |
| Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub, dan Oleksandr Skurzhanskyi | GECToR | Mendemonstrasikan transformasi yang ditandai dan koreksi berulang. | Pengaruh desain yang dievaluasi |
| Jonathan Mallinson, Jakub Adamek, Eric Malmi, dan Aliaksei Severyn | SuntingT5 | Menunjukkan penataan ulang berbasis penunjuk yang membatasi penemuan. | Pengaruh desain yang dievaluasi |
| Eric Malmi dan kolaborator; komunitas realisasi permukaan yang lebih luas | Pekerjaan realisasi berbasis tata bahasa, grafik-ke-teks, dan terbatas | Memperkuat pemisahan penentuan konten, perencanaan, realisasi, dan verifikasi. | Pengaruh arsitektur; tidak ada adopsi runtime menyeluruh |

## Spesialis penalaran, wacana, dan verifikasi

| Kontribusi | Sumber publik | Apa kontribusinya di sini | Hubungan |
|---|---|---|---|
| Elena Chistova dan kontributor IsaNLP | [Kartu model IsaNLP RST Parser v3](https://huggingface.co/tchewik/isanlp_rst_v3)dan karya ACL yang dikutip; catatan kartu model CC BY-NC 4.0 | Menghasilkan struktur wacana yang terikat dan calon relasi. Itu tidak menentukan makna pribadi. | Spesialis aktif; model digunakan dalam batasan izin non-komersialnya dan tidak didistribusikan ulang di sini |
| Shon Otmazgin, Arie Cattan, Yoav Goldberg, dan kontributor FastCoref | [Makalah F-COREF dan implementasi resminya](https://github.com/shon-otmazgin/fastcoref), MIT | Menghasilkan rantai intireferensi kandidat untuk validasi terikat sumber selanjutnya. | Spesialis aktif |
| Chris Reed, grup teknologi ARG, kontributor AIF/xAIF, dan kontributor AMF/ARI | [registri modul oAMF](https://github.com/arg-tech/oAMF),[Kumpulan data AIF dan registri model](https://github.com/arg-tech/aif-arg-datasets), dan spesifikasi tertaut | Mengklasifikasikan hubungan proposisi terbatas dan menyediakan kosakata grafik argumen yang dapat dioperasikan. | AMF/ARI adalah garis keturunan spesialis yang aktif; oAMF dievaluasi sebagai orkestrasi prior art daripada diadopsi secara grosir |
| Liyan Tang, Philippe Laban, dan Greg Durrett | [Periksa Mini](https://aclanthology.org/2024.emnlp-main.499/);[kode resmi](https://github.com/Liyan06/MiniCheck) | Pengamatan faktualitas yang efisien atas klaim dan dokumen landasan. | Spesialis yang dievaluasi; tidak melepaskan wewenang |
| Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching, dan Alex Deng | [FaktaCG](https://aclanthology.org/2025.naacl-long.258/);[kode resmi](https://github.com/derenlei/FactCG) | Pengamatan faktualitas multi-hop berdasarkan grafik. | Spesialis yang dievaluasi; tidak melepaskan wewenang |
| Philippe Laban, Tobias Schnabel, Paul N. Bennett, dan Marti A. Hearst | [SummaC](https://aclanthology.org/2022.tacl-1.10/) | Mengungkapkan masalah granularitas kalimat/dokumen dalam pemeriksaan konsistensi. | Pengaruh desain |
| Lorena Scire, Simone Conia, dan Roberto Navigli | [Pagar](https://arxiv.org/abs/2403.02270) | Ekstraksi klaim dan penyelarasan bukti untuk evaluasi peringkasan. | Pengaruh desain |
| Xiangkun Hu dan kolaborator | [Pemeriksa Ref](https://github.com/amazon-science/RefChecker) | Dukungan halus, sanggahan, dan catatan yang tidak diketahui. | Pengaruh desain yang dievaluasi |
| Trieu H. Trinh dan kolaborator | [AlfaGeometri](https://github.com/google-deepmind/alphageometry) | Penutupan deduksi monoton dan jejak ketergantungan bukti yang eksplisit. Aturan geometri tidak digunakan. | Pengaruh desain |

MiniCheck dan FactCG dievaluasi dengan revisi publik yang disematkan dan lisensi terbitannya. Skor mereka tidak dapat dipisahkan berdasarkan mutasi penting berbentuk proyek, sehingga mereka dikeluarkan dari otoritas rilis. Mempertahankan hasil negatif tersebut adalah bagian dari timbal balik: alat tersebut diberi penghargaan atas apa yang dapat mereka amati tanpa salah menggambarkan apa yang diklaim oleh penulisnya dapat mereka buktikan.

## Kontributor perangkat lunak

Proyek perangkat lunak publik berikut menyediakan mesin yang dibatasi. Pemberitahuan hak cipta dan lisensi masing-masing mengatur redistribusi kode mereka; dokumentasi publik ini tidak mendistribusikannya kembali.

| Perangkat lunak | Kontributor atau pelayan | Lisensi tercatat | Peran yang dibatasi |
|---|---|---|---|
| spaCy dan model bahasanya | Explosion AI, Matthew Honnibal, Ines Montani, dan kontributor | MIT | Part-of-speech, morfologi, penguraian ketergantungan, dan pengukuran struktural |
| Bling Api | Microsoft dan kontributor | MIT | Segmentasi kalimat |
| LemmInflect | Brad Jacob dan kontributor | MIT | infleksi bahasa Inggris |
| submodlib | Vishal Kaushal, Rishabh Iyer, Ganesh Ramakrishnan, dan kontributor DECILE | MIT | Seleksi submodular |
| NLTK | Steven Bird, Edward Loper, Ewan Klein, dan kontributor | Apache-2.0 | Akses korpus dan utilitas linguistik |
| NomorPy | Kontributor NumPy | BSD-3-Klausul | Array numerik dan matriks kesamaan |
| Sains | Kontributor SciPy | BSD-3-Klausul | Pengelompokan dan operasi statistik |
| JaringanX | Kontributor NetworkX | BSD-3-Klausul | Operasi dan pengukuran grafik terarah |
| berlutut | Kevin Arvai dan kontributor | BSD-3-Klausul | Deteksi titik lutut untuk kurva kalibrasi terukur |
| PyYAML | Kirill Simonov dan kontributor | MIT | Pertukaran konfigurasi terstruktur |
| httpx | Tom Christie dan kontributor | BSD-3-Klausul | Transportasi HTTP batas layanan |
| psikopg | Daniele Varrazzo dan kontributor | LGPL-3.0 | Akses PostgreSQL |
| Pydantik | Kontributor Pydantic | MIT | Validasi dan serialisasi yang diketik |
| BukaVINO | Intel dan kontributor | Apache-2.0 | Inferensi model terbatas jika dikonfigurasi |
| deskriptif teks | Lasse Hansen, Kenneth Enevoldsen, dan kontributor | Apache-2.0 | Keterbacaan, koherensi, dan pengukuran teori informasi |
| LFTK | Bruce W. Lee dan Jason Hyung-Jong Lee | Izin proyek publik; verifikasi dengan rilis apa pun yang didistribusikan ulang | Ekstraksi fitur linguistik dievaluasi untuk kalibrasi |

Tabel ini merupakan inventaris utama, bukan pengganti pemberitahuan ketergantungan yang dihasilkan mesin dalam distribusi kode di masa mendatang. Versi yang tepat, hash, lisensi transitif, dan teks lisensi lengkap harus menyertai rilis apa pun yang mendistribusikan ulang file perangkat lunak atau model.

## Karya budaya, corpora, arsip, dan komunitas

Analisis ini mengukur pola penyampaian dan sifat struktural. Kecuali jika lisensi terpisah mengizinkan reproduksi, keluaran publik berisi pengukuran agregat dan identitas sumber, bukan teks sumber.

| Sumber | Orang atau lembaga yang dikreditkan | Izin dan batas penggunaan | Kontribusi |
|---|---|---|---|
| Proyek Gutenberg | Michael S. Hart, Proofreader Terdistribusi, penulis, editor, penerjemah, dan sukarelawan yang berpartisipasi | Teks domain publik yang terverifikasi diukur; Persyaratan dan merek dagang edisi Project Gutenberg tetap dihormati. | Kalibrasi sastra dan bentuk produk jangka panjang |
| LibriVox | Pembaca sukarela, pengelola, dan penulis teks sumber domain publik | LibriVox mencatat teks domain publik dan mendedikasikan rekamannya untuk domain publik berdasarkan kebijakan yang dinyatakan. | Kalibrasi penyampaian lisan calon; tidak secara diam-diam dikumpulkan dengan cetakan |
| Korpus Coklat | W. Nelson Francis, Henry Kučera, Brown University, dan kurator | Digunakan melalui istilah korpus terdistribusi untuk pengukuran agregat. | Kontras register berlabel genre |
| Reuters-21578 | Reuters, David Lewis, dan kurator | Pengukuran agregat hanya berdasarkan persyaratan distribusi kumpulan data. | Perbandingan salinan kawat yang padat |
| Korps Obrolan NPS | Eric Forsyth, Jane Lin, Craig Martell, dan Sekolah Pascasarjana Angkatan Laut | Pengukuran agregat; teks pribadi tidak direproduksi secara publik. | Perbandingan obrolan antar manusia |
| Terjemahan Deklarasi Universal Hak Asasi Manusia | OHCHR PBB dan penerjemah | Terjemahan paralel diukur sebagai kontrol; atribusi dipertahankan. | Memisahkan pola protokol lintas bahasa dari kebiasaan bahasa Inggris |
| arXiv | Cornell University, arXiv, mengirimkan penulis, dan pengelola | Metadata diperlakukan sesuai dengan ketentuan yang dipublikasikan; abstrak tetap merupakan karya penulis dan tidak direproduksi. | Pengukuran register ilmiah memanjang |
| PubMed/MEDLINE | Perpustakaan Kedokteran Nasional AS, jurnal yang berpartisipasi, dan penulis | Pengukuran agregat saja; abstrak tidak didistribusikan ulang dan tidak ada dukungan NLM yang tersirat. | Perbandingan prosa ilmiah |
| Delpher | Koninklijke Bibliotheek, kontributor digitalisasi, penerbit, dan penulis | Pengukuran agregat hanya karena hak tingkat item berbeda-beda. | Perbandingan surat kabar jangka panjang |
| Wikipedia | Wikimedia Foundation dan editor kontributor | sumber CC BY-SA; tidak ada teks artikel yang direproduksi dalam publikasi ini. | Perbandingan register ensiklopedia |
| Tumpukan Melimpah | Stack Exchange dan komunitas penjawab | sumber CC BY-SA; tidak ada teks posting yang direproduksi di sini. | Perbandingan jawaban forum |
| Sampel Berita Peretas dan Mastodon | Operator platform dan penulis komunitas individu | Tidak ada lisensi konten menyeluruh yang diasumsikan; hanya observasi agregat non-identifikasi yang dapat dipublikasikan. | Perbandingan format modern yang bersifat eksplorasi |

Pengembalian timbal balik dari proyek publik bukanlah kepemilikan atas karya-karya tersebut. Ini adalah laporan yang dapat diaudit mengenai metode yang mereka aktifkan, batasan yang ditemukan, hipotesis gagal yang mereka bantu palsukan, dan pengukuran yang dapat digunakan kembali yang menjaga jalur kembali ke kontributornya.

Timbal balik juga mengatur penggunaan model eksternal. Menyediakan muatan kerja resmi untuk kontribusi terikat tidak menjadikan layanan eksternal sebagai pemilik korpus yang dikelola, seperti halnya menggunakan penelitian yang dipublikasikan tidak menghapus kepengarangannya. Kontribusi tersebut harus dikreditkan dan diukur, sedangkan sumber, otoritas, dan nilai berkelanjutan dari catatan yang mendasarinya tetap berbeda. Timbal balik mencegah derivasi yang bermanfaat menjadi alasan untuk menghancurkan konteks kemanusiaan dan memusatkan nilainya di dalam institusi penerima.

## Batasan hak dan kelengkapan

Status domain publik, akses terbuka, sumber terbuka, dan izin untuk analisis komputasi merupakan status hak yang berbeda. Buku besar mencatat dasar yang berlaku daripada memperlakukan “tersedia online” sebagai izin. Sumber yang memerlukan pengelakan, otorisasi yang tidak pasti, atau teori penggunaan wajar yang belum ditinjau tidak termasuk dalam kumpulan data publikasi baru.

Buku besar mencakup fondasi utama yang terlihat dalam dokumentasi publik. Proyek swasta memiliki inventaris yang berkembang lebih besar, termasuk kandidat yang dievaluasi dan ditolak. Rilis ilmiah atau perangkat lunak di masa depan harus menghasilkan tagihan bahan perangkat lunak khusus artefak, buku besar model dan kumpulan data, bibliografi, bundel lisensi, dan catatan transformasi. Kelalaian dari ringkasan ini tidak menghapus kredit atau memberikan izin.
