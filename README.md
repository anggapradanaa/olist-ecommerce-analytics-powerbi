# Laporan Insight Dashboard Olist E-Commerce

---

## 1. Revenue Performance

### Temuan

Olist mencatat pertumbuhan revenue yang sangat agresif sepanjang 2017, dari R$127,5 ribu pada Januari 2017 hingga puncaknya di **November 2017 sebesar R$1,15 juta**, mewakili pertumbuhan lebih dari 800% dalam satu tahun. Memasuki 2018, revenue stabil di kisaran **R$966 ribu hingga R$1,13 juta per bulan** (Januari hingga Agustus 2018) tanpa lonjakan berarti. Total revenue keseluruhan mencapai **R$15,42 juta** dari **96.480 transaksi** dengan rata-rata nilai order R$159,83.

Dari sisi distribusi harga, rentang **R$100 hingga R$250** menjadi kontributor revenue terbesar (R$5,3 juta), diikuti produk di atas R$500 dan R$50 hingga R$100 yang masing-masing menyumbang R$3,0 juta. Dari sisi kategori, **Health & Beauty** memimpin dengan revenue R$1,4 juta (9,28% revenue share), diikuti Watches & Gifts (R$1,3 juta), Bed, Bath & Table (R$1,2 juta), Sports & Leisure (R$1,1 juta), dan Computers & Accessories (R$1,0 juta).

Di sisi pertumbuhan YoY, kategori dengan lonjakan tertinggi adalah Small Appliances, Diapers & Hygiene, Arts & Craftsmanship, Construction Tools & Lights, dan Cine & Photo — meskipun nilai absolutnya masih kecil. Sebaliknya, Security & Services (-100%), CDs & DVDs (-86%), Fashion Sport (-81%), Tablets & Printing (-79%), dan Fashion Male Clothing (-71%) mencatat penurunan tajam. Metode pembayaran didominasi oleh **credit card sebesar 75,31%** dari seluruh transaksi.

### Interpretasi

Stabilnya revenue di 2018 mengindikasikan Olist telah memasuki fase **growth maturity**. Pertumbuhan tidak lagi bisa hanya mengandalkan penambahan volume transaksi, karena kurva pertumbuhan sudah mendatar. Dominasi rentang harga R$100 hingga R$250 menunjukkan segmen mid-range sebagai tulang punggung bisnis, sementara produk di atas R$500 membuktikan bahwa segmen premium tetap relevan meskipun volumenya kecil. Penurunan tajam pada beberapa kategori seperti Fashion dan Tablets merupakan sinyal pergeseran preferensi konsumen yang perlu diantisipasi.

### Rekomendasi

Karena revenue sudah mendatar, fokus pertumbuhan perlu bergeser dari menambah jumlah transaksi menjadi **meningkatkan nilai per transaksi**. Kategori dengan average order value tinggi seperti Computers & Accessories dan Watches & Gifts dapat didorong melalui program bundling atau penawaran cicilan berbasis credit card, mengingat dominasi metode pembayaran tersebut sudah mencapai 75,31%. Untuk kategori yang mengalami penurunan YoY tajam, perlu dilakukan evaluasi apakah penurunan disebabkan oleh faktor permintaan atau masalah pada sisi seller dan kualitas produk, sebelum memutuskan apakah kategori tersebut perlu dipertahankan atau dikurangi porsinya di platform.

---

## 2. Customer Segmentation (RFM)

### Temuan

Distribusi pelanggan berdasarkan segmen RFM adalah sebagai berikut:

| Segmen | Jumlah Pelanggan | % Total | Avg Recency (hari) | Avg Monetary (R$) | Total Revenue (R$) |
|---|---|---|---|---|---|
| Need Attention | 15.402 | 16,50% | 394,2 | 88,18 | 1.358.196 |
| Champions | 15.162 | 16,24% | 91,6 | 309,08 | 4.686.294 |
| At Risk | 14.542 | 15,58% | 393,7 | 309,29 | 4.497.750 |
| Recent Customers | 14.351 | 15,37% | 90,2 | 55,49 | 796.334 |
| Potential Loyalists | 11.112 | 11,90% | 220,8 | 225,50 | 2.505.799 |
| Others | 10.912 | 11,69% | 250,7 | 50,30 | 548.864 |
| Loyal Customers | 7.829 | 8,39% | 90,8 | 107,34 | 840.341 |
| Lost | 3.884 | 4,16% | 475,9 | 42,11 | 163.557 |
| Promising | 164 | 0,18% | 218,3 | 138,04 | 22.638 |

Dari sisi frekuensi transaksi, sekitar **91 ribu pelanggan (hampir 97%) hanya melakukan satu kali transaksi**, sementara pelanggan dengan 2 order hanya sekitar 3 ribu, dan pelanggan dengan 3 order ke atas hampir tidak terlihat secara statistik. Secara geografis, São Paulo mendominasi dengan sekitar **40 ribu pelanggan (40% dari total)**, diikuti Rio de Janeiro (12 ribu) dan Minas Gerais (11 ribu).

### Interpretasi

Dua temuan paling kritis di sini adalah soal **segmen At Risk** dan **dominasi one-time buyers**. Segmen At Risk menyimpan R$4,50 juta revenue dengan rata-rata monetary R$309 per pelanggan — hampir identik dengan Champions — namun recency-nya sudah 393,7 hari. Artinya, pelanggan paling bernilai ini sudah tidak bertransaksi hampir selama setahun penuh. Jika tidak diintervensi, segmen ini akan bermigrasi ke segmen Lost dan kehilangan ini akan langsung terasa pada revenue.

Lebih jauh, fakta bahwa 97% pelanggan hanya bertransaksi sekali menunjukkan bahwa Olist belum berhasil membangun **customer loyalty** sama sekali. Ini berarti bisnis harus terus mengeluarkan biaya akuisisi pelanggan baru untuk mempertahankan level revenue yang sama, tanpa pernah memaksimalkan nilai dari pelanggan yang sudah ada.

### Rekomendasi

Prioritas pertama adalah **reaktivasi segmen At Risk**. Dengan rata-rata monetary R$309 dan total potensi revenue R$4,50 juta, bahkan jika hanya 20% dari segmen ini berhasil diaktifkan kembali, dampaknya sudah sekitar R$900 ribu revenue tambahan. Reaktivasi dapat dilakukan melalui penawaran personal berbasis kategori produk yang pernah mereka beli sebelumnya, mengingat data histori transaksi tersedia di platform.

Prioritas kedua adalah **konversi Recent Customers** (14.351 pelanggan, recency 90,2 hari) sebelum mereka mendingin. Segmen ini masih aktif namun rata-rata monetary baru R$55,49 — jauh di bawah Champions. Intervensi di fase ini jauh lebih murah dibanding reaktivasi di kemudian hari.

Prioritas ketiga adalah **mengembangkan Potential Loyalists** (11.112 pelanggan, avg monetary R$225,50) menuju level Champions. Segmen ini sudah menunjukkan nilai transaksi yang cukup tinggi dan recency yang moderat, sehingga memiliki probabilitas konversi yang lebih baik dibanding segmen lain.

---

## 3. Delivery & Seller Performance

### Temuan

Dari 96.470 pesanan yang berhasil dikirim, **89.240 pesanan (92,5%) tiba tepat waktu atau lebih awal** dengan rata-rata waktu pengiriman 12,10 hari. Tingkat keterlambatan berada di angka 6,77%. Dampak keterlambatan terhadap review score:

| Kondisi Pengiriman | Total Orders | Avg Review Score |
|---|---|---|
| On Time / Early | 89.240 | 4,29 |
| Late 1-3 hari | 1.843 | 3,29 |
| Late 4-7 hari | 1.746 | 2,11 |
| Late 8-14 hari | 1.439 | 1,67 |
| Late 15+ hari | 1.333 | 1,72 |

Dari sisi seller, distribusi revenue menunjukkan:

| Kategori Seller | Total Sellers | Total Revenue (R$) | Avg Review Score | Avg Orders |
|---|---|---|---|---|
| Star Seller | 216 | 7.213.029 | 4,26 | 190,76 |
| Average | 248 | 3.822.374 | 3,76 | 116,13 |
| High Rating – Low Revenue (Potential) | 335 | 1.673.810 | 4,33 | 45,82 |
| High Revenue – Low Rating (At Risk) | 5 | 92.324 | 2,79 | 111,20 |

Secara geografis, seller São Paulo mendominasi dengan 1.769 seller, 68.641 orders, dan revenue R$9,98 juta. Wilayah lain seperti Paraná (R$1,43 juta) dan Minas Gerais (R$1,19 juta) jauh tertinggal meskipun rata-rata review score mereka kompetitif di kisaran 4,13 hingga 4,17.

### Interpretasi

Data delivery menunjukkan adanya **threshold kritis di angka 3 hari keterlambatan**. Di bawah 3 hari, pelanggan masih cukup toleran dengan score 3,29. Namun begitu keterlambatan melewati 4 hari, score anjlok ke 2,11 — penurunan lebih dari 1 poin hanya karena selisih satu hari. Ini menunjukkan bahwa persepsi pelanggan terhadap keterlambatan bersifat **non-linear**: toleransi ada, tapi begitu batas itu terlampaui, kepuasan runtuh dengan cepat.

Dari sisi seller, 216 Star Seller menyumbang lebih dari 55% total revenue platform, menciptakan **ketergantungan struktural** yang berisiko. Sementara itu, 335 seller dalam kategori High Rating – Low Revenue justru memiliki rata-rata review score tertinggi (4,33) namun rata-rata order terendah (45,82). Ini bukan masalah kualitas, melainkan masalah visibilitas.

### Rekomendasi

Untuk delivery, fokus intervensi sebaiknya tidak hanya pada mengurangi jumlah keterlambatan secara keseluruhan, tetapi secara spesifik pada **mencegah keterlambatan melewati batas 3 hari**. Pesanan yang sudah terlambat 1-2 hari perlu mendapat prioritas eskalasi segera, karena dari data terlihat bahwa membiarkannya berlanjut ke hari ke-4 menghasilkan penurunan kepuasan yang jauh lebih besar daripada keterlambatan itu sendiri.

Untuk seller, prioritas utama adalah **mendorong pertumbuhan segmen High Rating – Low Revenue**. Dengan review score rata-rata 4,33 — bahkan melampaui Star Seller — kualitas seller di segmen ini sudah terbukti. Yang dibutuhkan adalah peningkatan exposure melalui mekanisme platform seperti prioritas penempatan produk atau inclusion dalam program promosi. Selain itu, 5 seller dalam kategori High Revenue – Low Rating dengan score 2,79 perlu ditangani segera melalui pembinaan atau penerapan standar minimum kualitas, sebelum rating rendah mereka berdampak lebih luas pada persepsi platform.

Dari sisi geografis, wilayah seperti Minas Gerais, Rio de Janeiro, dan Paraná menunjukkan kualitas seller yang kompetitif namun kontribusi revenue yang masih jauh di bawah São Paulo. Ekspansi ekosistem seller ke wilayah-wilayah ini merupakan peluang nyata untuk mengurangi ketergantungan pada satu region dan mendiversifikasi sumber revenue platform.

---

## Kesimpulan Strategis

Olist berada pada titik transisi penting. Fase pertumbuhan agresif sudah berakhir, dan data menunjukkan tiga prioritas utama yang harus ditangani secara bersamaan.

Pertama, masalah **retensi pelanggan** adalah yang paling mendesak. Dengan 97% pelanggan tidak pernah kembali dan R$4,50 juta revenue tersimpan di segmen At Risk yang hampir tidak aktif, setiap bulan tanpa intervensi adalah potensi revenue yang hilang permanen.

Kedua, **ketergantungan pada Star Seller dan region São Paulo** menciptakan risiko konsentrasi yang nyata. Pertumbuhan jangka panjang membutuhkan diversifikasi ekosistem seller, dan data sudah menunjukkan bahwa kapasitas kualitasnya ada di segmen High Rating – Low Revenue.

Ketiga, **threshold keterlambatan pengiriman di 3 hari** harus menjadi standar operasional yang dijaga ketat, bukan sekadar target rata-rata, karena dampaknya terhadap kepuasan pelanggan terbukti non-linear dan langsung memengaruhi persepsi kualitas platform secara keseluruhan.
