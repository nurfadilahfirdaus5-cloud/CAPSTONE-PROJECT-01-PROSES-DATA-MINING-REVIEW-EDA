# CAPSTONE-PROJECT-01-PROSES-DATA-MINING-REVIEW-EDA

# Studi Kasus EDA PT Ray Pink Property Indonesia (RPPI)

## Kasus
Anda adalah seorang Data Analyst yang bekerja di PT Ray Pink Property Indonesia (RPPI).  
RPPI adalah perusahaan property yang berdiri sejak 11 tahun yang lalu.  
RPPI memliki kantor cabang di 7 propinsi di Indonesia dan jumlahnya terus bertambah.  
Valuasi RPPI tahun ini mencapai Rp 7 Trilyun, meningkat 7% dari tahun sebelumnya.  
Bidang usaha RPPI adalah investasi dan jual-beli property secara umum, termasuk bekerja sama dengan developer perumahan.  
Data Engineer (DE)/Database Administrator (DBA) RPPI berhasil mengumpulkan data rumah-rumah yang dijual di beberapa kota di Indonesia.  
Sebagai Data Analyst anda akan hadir dan melakukan presentasi pada rapat direksi untuk memberikan insight dari data ke upper management (C-Level, senior managers, dan komisaris perusahaan.  
Di studi kasus ini anda mempersiapkan "bahan presentasi" dengan cara melakukan EDA pada data yang diterima dari DE/DBA.

---

## Petunjuk
Di studi kasus pertama, anda mendapat bantuan keterangan dari manajemen. Setelah berdiskusi over lunch dengan beberapa manager senior, anda mendengar bahwa mereka ingin mengetahui:

- Kualitas data yang dimiliki perusahaan.  
- Apakah ada saran perbaikan data ke DE/DBA perusahaan agar RPPI menjadi data driven company yang unggul.  
- Dari data yang ada, apakah ada kecenderungan rumah disuatu kota lebih mahal/murah dibandingkan kota lain?  
- Dari data yang ada, apakah bisa dibuat rekomendasi sebaiknya RPPI membuat kantor cabang berikutnya di kota mana? Mengapa? (Asumsikan RPPI belum memiliki cabang di kota-kota yang disebutkan di data).  
- Rumah dengan karakteristik seperti apa yang paling banyak dijual?  
- Jika RPPI ingin melakukan investasi (max) Rp. 25 Milyar minggu besok, apakah dari data anda dapat memberikan rekomendasi rumah mana saja yang akan berpotensi menghasilkan keuntungan bagi perusahaan?  
- Dan yang terpenting, informasi berharga apa lagi yang bisa anda dapatkan dari data?

---

## Catatan
- Anda diperbolehkan melakukan augmentasi data (menambah data eksternal).  
- Yakinkan menuliskan asumsi anda atas kesimpulan dan rekomendasi yang diberikan ke perusahaan.  
- Yakinkan kesimpulan dan rekomendasi ditujukan ke perusahaan (bukan dosen mata kuliah).  
- Anda boleh menggunakan software visualisasi apapun, misal excel, Ms Word, Photoshop, dsb.  
- Yakinkan file images dapat dibuka (nampak) saat ipynb di Jupyter notebook anda dibuka di Google Colab.  
- Tips: hati-hati dalam melakukan penamaan file, Google colab case sensitive.  
- Interpretasi diberikan menggunakan cell markdown tepat dibawah output code yang relevan diatasnya.  
- Anda tidak diperkenankan bertanya pertanyaan yang:  
  - Merupakan jawaban atau menjurus ke jawaban studi kasus.  
  - Debugging - code error (anda diharapkan melakukan code troubleshooting sendiri via mesin pencari)  
- Pada studi kasus ini anda hanya diperkenankan untuk melakukan EDA (bukan modeling seperti prediksi/forecasting)

---

## Komponen Penilaian
- Code tidak diubah sejak deadline studi kasus.  
- Code dapat di "Run-All" di Google Colab oleh dosen tanpa error.  
- Pemilihan preprocessing dan visualisasi yang tepat  
- Interpretasi dan rekomendasi dengan narasi dan kualitas yang baik, serta berdasarkan atas (pengolahan) data.  
- Kreativitas dan inovasi pengolahan data dan penyajian visualisasi.

---

## Data Understanding (DU)
**Keterangan Varabel:**

- Created_at: Tanggal dimana iklan rumah dibuat  
- LT : Luas Tanah properti yang ditawarkan  
- LB : Luas Bangunan properti yang ditawarkan  
- KT : Jumlah Kamar Tidur properti yang ditawarkan  
- KM : Jumlah Kamar Mandi properti yang ditawarkan  
- Garasi : Jumlah Kapasitas Garasi di properti yang ditawarkan  
- Carport : Kapasitas Carport di properti yang ditawarkan  
- Lokasi : Detail lokasi properti yang ditawarkan  
- Sertifikat: Jenis sertifikat properti yang ditawarkan  
- Listrik : Daya listrik dari properti yang ditawarkan  
- Hadap : Keterangan property yang ditawarkan menghadap ke arah mana  
- Harga : Harga property yang ditawarkan dalam Rupiah  
- URL : Alamat tautan (link) property yang ditawarkan.  
- Deskripsi : Deskripsi iklan property yang ditawarkan.
