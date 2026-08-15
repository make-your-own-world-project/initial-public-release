> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Bagaimana Sistem Bertahan Bersama

![Catatan yang disimpan mendukung spesialis yang dapat diganti dan pesawat kendali yang dapat diperiksa](../../assets/core-architecture-layers.png)

## Pemisahan tanggung jawab

Platform ini memisahkan empat kepentingan yang bekerja sama tanpa menjadi satu sama lain:

1. **Pelestarian** mempertahankan bukti asli dan asal usul yang diamati.
2. **Pemahaman** menambahkan objek semantik berversi, hubungan, keadaan temporal,
  dan mendukung interpretasi.
3. **Pengambilan dan interaksi** mengumpulkan bukti khusus permintaan untuk pertanyaan,
  eksplorasi, dan percakapan.
4. **Rekonstruksi artefak** mengubah dunia bukti yang terbatas menjadi dunia yang dinyatakan
  produk untuk penerima yang dinyatakan.

Instruksi produk tidak bocor ke belakang ke dalam kebenaran korpus. Sebuah bab, penonton, genre, gerakan retoris, atau anggaran kata termasuk dalam satu penarikan. Ini bukan label intrinsik pada artefak sumber.

## Topologi berlapis

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## Aksesi tidak berpura-pura tahu

Catatan kedatangan mungkin menyatakan bahwa byte tertentu mencapai sistem melalui saluran tertentu. Ia tidak secara diam-diam memutuskan siapa yang membuat artefak, siapa yang muncul di dalamnya, kapan subjeknya muncul, apakah nama filenya akurat, mengapa itu penting, atau siapa pemilik kontennya. Itu adalah pengamatan terpisah dengan bukti dan otoritas terpisah.

Arsitektur membedakan artefak asli dari representasi yang diturunkan darinya. Teks, deskripsi, penyematan, klasifikasi, ringkasan, dan hubungan yang diekstraksi dapat dibuat ulang atau digantikan. Mereka tidak menggantikan sumbernya.

## Jalur interaktif dan dokumen

Jawaban interaktif dan pembuatan artefak berbagi bukti, asal, hubungan yang diketik, ketidakpastian, dan mekanisme validasi. Mereka tetap berbeda dari alur kerja yang sama.

Permintaan interaktif mungkin memerlukan percakapan lengkap, siklus hidup tugas, traversal hubungan yang sempit, atau klarifikasi. Tidak perlu membangun wadah buku dan merobohkan pohon sejarah secara global.

Pembuatan artefak memang memerlukan produk, penerima, anggaran, dan rencana keseluruhan artefak yang dinyatakan. Ia harus melihat struktur sementara yang relevan sebelum pemangkasan dan harus memperhitungkan apa yang tertinggal.

## Arsitektur dinamis, bukan rantai tetap

Jalur perakitan dikompilasi untuk produk. Output yang berbeda dapat menggunakan spesialis yang berbeda, memesan spesialis yang sama secara berbeda, atau memerlukan beberapa contoh dari satu kemampuan. Manajer menggunakan kontrak kemampuan dan bukti sebelumnya, bukan hanya nama panggung yang dikodekan secara keras.

Invarian universal tetap stabil di setiap lini: identitas sumber, kepemilikan, keadaan epistemik, ketidakpastian, akuntansi kerugian, penyerahan yang diketik, observasi biaya, verifikasi independen, dan rollback.

Model umum eksternal dapat menempati satu stasiun yang diketik ketika kontribusi terukurnya membenarkan penyerahan tersebut. Ia hanya menerima muatan dengan cakupan permintaan yang diperlukan oleh stasiun tersebut, bukan korpus yang dikelola atau otoritas yang dikodekan oleh bidang kendali yang lebih luas. Mengganti atau menghapus stasiun tersebut akan meninggalkan catatan yang tahan lama dan kemampuan rekonstruksi di masa depan tetap utuh. Stasiun yang dibatasi dapat berkontribusi tanpa menerima pengetahuan manusia, sehingga sistem terpusat akan menjadi nilai institusional.
