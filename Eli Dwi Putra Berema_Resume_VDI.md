
<tr>
    <td>Nama: Eli Dwi Putra Berema</td>
</tr>

NIM: 122450064 / Matkul: Visualisasi Data dan Informasi

# Data Visualization
    Data Visualization atau visualisasi data bertujuan untuk mengubah suatu baris data (record) kedalam suatu bentuk visual yang lebih mudah dicerna oleh manusia yang merupakan mahluk visual.
Dalam hal ini kita dapat mengubahnya menajdi suatu bentuk grafik dan memberikan warna yang dapat mepermudah penyapaian informasi dari data, sebagai contoh:
| Nama       | Gambar    |
|------------|------------|
| Bar Chart   | ![Bar Chart](https://datavizproject.com/wp-content/uploads/types/Multiple-Series-3D-Bar-Chart-300x300.png)
   |
| Heatmap  | ![ Heatmap](https://datavizproject.com/wp-content/uploads/types/Heat-Map-300x300.png)   |
|  Scatter Plot  | ![Scatter PLot](https://datavizproject.com/wp-content/uploads/types/Scatter-Plot-300x300.png)  | 

Di era modern ini visualisasi data telah menjadi hal yang populer. Dengan banyaknya data yang ada saat ini, kita perlu merubahnya menjadi hal yang umum dan mudah dimengerti oleh khalayak umum.

## The Pipeline of Data Visualization
![Data Pipeline](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSN66C7DM87jjA6LdY8T0UXh5rEcVrh-RTxuKYmUYLQqoJRt5Qr)

1. *Data *import**, mengumpulkan data yang dibutuhkan 
2. *Data Preparation*, memperisapkan dengan menormalisasi dan membersihkan data
3. *Data Manipulation*, mengambil hal terpenting dan paling dibutuhkan dalam suatu data
4. *Mapping*, mengubag hasil manipulasi data menjadi suatu bentuk geometrik
5. *Render*, mengubah hasil mapping menjadi suatu visual yang respresentatif

Berdasarkan 5 pipeline ini kita telah menemukan 3 cara unutk membuat suatu visualisasi data menjadi hal yang lebih efektif dan efisien.
1. spesifikasi visualisasi, menentukan secara sepesifik apa yang dibutuhkan oleh user, yang terbagi menjadi
   - *self-comopletenes*, pentingnya mengetahui pembuatan data visualization.
   - *language design perspective* memetakan beberapa informasi menjadi suatu elemen visual
2. pendekatan efisiensi untuk data visualization, dalam hal ini diperkan pembuatan yang efesien dan efektif. terutama pada komopoenen data manipilation dan mapping.
3. rekomendasi vialisasi data, diperlukan karena dengan begini kita dapat mengetahui visalisasi apa yang dibutuhkan oleh user

# Spesifikasi Visualisasi
Visuaslisasi data berlatarkan 3 bagian yaitu data, penanda visual dan pemetaan
- data
  - records: baris data yang diperlukan
  - transformasi: operasi yang mbetujuan untuk mengubah records secaara sepsifik
- penanda visual
  - tipe: bentuk visuali yang merepresentasikan record seperti titik dan garis
  - ukuran: panjang dan lebarnya suatu visualisasi
  - legend: infomasi tambahan yang menjelaskan visualisasi data secara singkat
- pemetaan: memetakan hasil penanda visual menjadi hal yang lebih kompleks

# Kategori bahasa yang digunakan dalam visualisasi data
- Low-level Languages
  merupakan bahasa pemograman yang paling dekat dengan bahasa mesin yang biner, meskipun kurang umum dalam dijadikan alat pemvisualan, bahasa ini cocok unutk pengembangan
- High-level languages, merupakan bahasa yang paling umum digunakna dalam visualisasi data yang memudahkan pengunakan yang dekat dengan bahasa manusia
- Gui-Based, tidak seperti high level gui-based menyediakan interaksi anatarmuka terhadap pengunkan yang menjadikan lebih mudah untuk digunakan dari high level yang masih memerlukan kode
- Underspecified specifications, berbeda dengan 3 kotegori diatas, uderspevified hanya memberikan suatu petunjuk atau klue secara samar.
  
# 3 pendekatan efisien dalam pemvisualisasian data
- **Pemvisualisasian data secara pasti**, hampir semua sistem pemvisualan data mengambil data dari suatu basis data. Dengan ini kita dapat meningkatkan proses ekplorasi visual, dengan mengunakan DBMS
- **Memperkirakan suatu visualisasi data**, dengan ini ita dapat memungkinkan kita untuk membuat visualisasi secara cepat dan singkat dengan menggunakan APQ, sample dan presepsi
- **Pemvisualisasian secara bertahap**, dengan ini kita dapat memahami dan mengeksplorasi data secara dinamis. Dalam hal ini kita memerlukan teknik hierarchical aggregation

# Visualization Recomendation
visualization recommendation dirancang untuk mengurangi hambatan dalam menjelajahi visualisasi dasar dengan secara otomatis menyediakan hasil yang dapat dipilih oleh analis, alih-alih menentukan secara manual. Dalam penelitian ini, kami menunjukkan metode baru berbasis pembelajaran mesin untuk visualization recommendation yang mempelajari pilihan desain visualisasi dari kumpulan data dan visualisasi terkait yang luas. Kami mengidentifikasi lima pilihan desain utama yang dipertimbangkan oleh analis, seperti memilih jenis visualisasi dan menentukan pengkodean kolom pada sumbu X atau Y. Kami melatih model untuk memprediksi pilihan desain ini menggunakan satu juta pasangan data-visualisasi yang diambil dari platform visualisasi online populer. Jaringan saraf kami memprediksi pilihan desain dengan akurasi tinggi dibandingkan dengan model dasar. Kami melaporkan dan menginterpretasikan pentingnya fitur dari salah satu model dasar tersebut. Untuk menguji kemampuan generalisasi dan ketidakpastian metode kami, kami melakukan evaluasi dengan set pengujian yang dikumpulkan dari crowdsourcing, dan menunjukkan bahwa performa model kami sebanding dengan manusia dalam memprediksi jenis visualisasi yang disepakati serta melebihi sistem visualization recommendation lainnya.