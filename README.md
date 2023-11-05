Link Jurnal :
1. https://ieeexplore.ieee.org/document/9138372/
2. https://ieeexplore.ieee.org/document/9795021/

Progres Riset
Bab III
Metodologi Penelitian

  Bab ini menjelaskan metodologi yang akan digunakan dalam penelitian pengembangan Sistem Live Attendance dengan Teknologi Pengenalan Wajah menggunakan Convolutional Neural Network (CNN) di PT. Setia Kawan Makmur Sejahtera Tulungagung. Metodologi ini mencakup tahapan penelitian, alat dan bahan yang digunakan, serta langkah-langkah yang akan diambil untuk mencapai tujuan penelitian.

3.1. Desain Penelitian

Penelitian ini akan menggunakan desain penelitian eksperimen yang melibatkan pengembangan dan implementasi sistem Live Attendance dengan Teknologi Pengenalan Wajah menggunakan CNN. Metode eksperimen akan digunakan untuk menguji dan mengukur efektivitas sistem dalam memantau kehadiran karyawan di PT. Setia Kawan Makmur Sejahtera.

3.2. Lokasi Penelitian

Penelitian ini akan dilaksanakan di PT. Setia Kawan Makmur Sejahtera, yang berlokasi di Tulungagung, Jawa Timur. Lokasi ini dipilih karena merupakan tempat di mana sistem Live Attendance akan diimplementasikan.

3.3. Populasi dan Sampel

Populasi penelitian ini terdiri dari seluruh karyawan PT. Setia Kawan Makmur Sejahtera yang akan menggunakan sistem Live Attendance. Sampel penelitian akan dipilih secara acak dari populasi tersebut.

3.4. Alat dan Bahan

- Perangkat Kamera:
  Kamera wajah yang akan digunakan untuk mengambil gambar wajah karyawan.
- Perangkat Komputer:
  Komputer yang akan digunakan untuk melatih model CNN dan menjalankan sistem Live Attendance.
- Dataset Gambar Wajah Karyawan:
  Dataset gambar wajah karyawan yang akan digunakan untuk melatih model pengenalan wajah.
- Perangkat Lunak:
  Perangkat lunak seperti TensorFlow, Keras, dan OpenCV untuk pengembangan dan implementasi sistem Live Attendance.
- Database Karyawan:
  Database yang berisi informasi karyawan dan data wajah mereka.

3.5. Tahap Penelitian

Penelitian ini akan melibatkan beberapa tahap penting yang meliputi:

  3.5.1. Pengumpulan Data
  Pada tahap pengumpulan data, langkah-langkah berikut akan dilakukan:
  1. Pengumpulan Dataset Gambar Wajah Karyawan:
      Untuk mengumpulkan dataset gambar wajah karyawan, kamera yang terhubung dengan sistem Live Attendance akan digunakan. Kamera ini akan ditempatkan pada lokasi yang strategis di PT. Setia       Kawan Makmur Sejahtera. Setiap kali seorang karyawan melakukan kehadiran atau registrasi di sistem Live Attendance, kamera akan mengambil gambar wajah karyawan. Gambar ini akan digunakan       sebagai dataset untuk melatih model pengenalan wajah. Selama pengambilan gambar, upaya akan dilakukan untuk memastikan pencahayaan yang memadai dan resolusi gambar yang cukup tinggi agar       model pengenalan wajah dapat berkinerja optimal.
  2. Pengumpulan Data Informasi Karyawan:
      Selain gambar wajah, informasi karyawan seperti nama, nomor identitas, dan jadwal kerja juga akan dikumpulkan. Informasi ini diperlukan untuk membangun database yang akan digunakan dalam      sistem Live Attendance. Data ini dapat diperoleh melalui registrasi karyawan pada sistem atau dengan metode lain yang sesuai. Pengumpulan data informasi karyawan akan memastikan bahwa     
     sistem dapat mencocokkan wajah dengan informasi yang tepat tentang karyawan yang bersangkutan.

   Pengumpulan data ini adalah langkah awal penting dalam mengembangkan sistem Live Attendance dengan Teknologi Pengenalan Wajah menggunakan CNN. Data yang akurat dan representatif akan 
  menjadi dasar bagi tahapan selanjutnya dalam penelitian ini, termasuk pelatihan model CNN dan implementasi sistem Live Attendance.

 3.5.2. Pra-Pemrosesan Data
 Pada tahap pra-pemrosesan data, langkah-langkah berikut akan dilakukan untuk memastikan data gambar wajah dan informasi karyawan siap digunakan dalam pengembangan Sistem Live Attendance:

1. Pemrosesan Data Gambar Wajah:
- Normalisasi Gambar:
   Gambar wajah yang diambil dari kamera mungkin memiliki berbagai resolusi, tingkat pencahayaan, dan orientasi yang berbeda. Sebelum gambar-gambar ini digunakan dalam pelatihan model, mereka  
  akan dinormalisasi. Ini termasuk mengubah semua gambar menjadi ukuran yang konsisten, menyesuaikan tingkat kecerahan dan kontras, dan memastikan bahwa gambar berada dalam format yang 
  kompatibel dengan model CNN yang akan digunakan.
- Penghapusan Noise:
   Gambar wajah dapat mengandung noise atau gangguan yang dapat mempengaruhi performa model. Oleh karena itu, langkah pra-pemrosesan ini akan mencakup penghapusan noise atau penyaringan gambar 
  untuk menghilangkan gangguan yang tidak relevan.
- Ekstraksi Fitur:
   Dalam beberapa kasus, ekstraksi fitur dapat dilakukan untuk mengidentifikasi fitur wajah yang relevan seperti mata, hidung, dan mulut. Ini akan membantu model dalam mengenali wajah dengan 
  lebih baik.

2. Pemrosesan Data Informasi Karyawan:
- Validasi Data Karyawan:
   Informasi karyawan yang telah dikumpulkan akan divalidasi untuk memastikan bahwa tidak ada data yang tidak lengkap atau salah. Misalnya, memeriksa apakah semua karyawan memiliki nomor 
  identitas yang unik dan informasi jadwal kerja yang tepat.
- Pengorganisasian Data:
   Data informasi karyawan akan diorganisasi dalam format yang sesuai dan dapat diakses oleh sistem Live Attendance. Database akan disusun sehingga sistem dapat mencocokkan wajah yang 
  diidentifikasi dengan data karyawan yang bersangkutan.
  
Tahap pra-pemrosesan data ini sangat penting untuk memastikan bahwa data yang digunakan dalam pelatihan model dan implementasi sistem Live Attendance adalah data yang berkualitas tinggi dan siap digunakan. Dengan pemrosesan yang tepat, performa sistem dapat ditingkatkan dan hasilnya akan lebih andal.

3.5.3. Pelatihan Model CNN
Pada tahap pelatihan model CNN, langkah-langkah berikut akan dilakukan untuk mengembangkan model pengenalan wajah:

1. Membangun Arsitektur Model CNN:
    Arsitektur model Convolutional Neural Network (CNN) akan dirancang untuk tujuan pengenalan wajah. Ini mencakup pemilihan jumlah lapisan (layers), jenis lapisan (seperti Convolutional 
   layers, Pooling layers, dan Fully Connected layers), serta hyperparameter yang sesuai. Arsitektur ini akan dibuat dengan mempertimbangkan kebutuhan pengenalan wajah yang akurat dan efisien.
3. Inisialisasi Bobot Model:
    Bobot awal (weights) model akan diinisialisasi dengan nilai acak atau, dalam beberapa kasus, dengan menggunakan teknik transfer learning. Transfer learning melibatkan penggunaan bobot dari 
   model CNN yang telah dilatih pada dataset besar (misalnya, model yang dilatih pada dataset gambar umum), dan kemudian melakukan penyesuaian untuk tugas pengenalan wajah.
5. Pelatihan Model:
    Model akan dilatih menggunakan dataset gambar wajah karyawan yang telah di pra-pemrosesan sebelumnya. Selama pelatihan, model akan belajar untuk mengenali fitur wajah yang unik dari setiap 
   individu karyawan. Proses pelatihan akan melibatkan pengoptimalan bobot model sehingga model dapat memberikan hasil pengenalan wajah yang akurat.

3.5.4. Implementasi Sistem Live Attendance
Pada tahap implementasi sistem Live Attendance, langkah-langkah berikut akan dilakukan:

1. Integrasi Model CNN:
    Model CNN yang telah dilatih akan diintegrasikan ke dalam sistem Live Attendance. Ini akan memungkinkan sistem untuk menggunakan model untuk mengenali wajah karyawan saat melakukan 
   kehadiran.
2. Implementasi Pengenalan Wajah:
    Pengenalan wajah akan diimplementasikan dalam sistem Live Attendance. Ketika seorang karyawan hadir, kamera akan mengambil gambar wajahnya, dan sistem akan menggunakan model untuk 
   mengenali wajah tersebut. Informasi kehadiran karyawan akan dicatat dan disimpan.

3.5.5. Pengujian dan Evaluasi
Pada tahap pengujian dan evaluasi, langkah-langkah berikut akan dilakukan:

1. Pengujian Sistem Live Attendance:
    Sistem Live Attendance akan diuji dengan menggunakan data kehadiran karyawan yang sebenarnya. Selama pengujian, karyawan akan melakukan kehadiran sesuai jadwal mereka, dan sistem akan 
   mencoba mengenali wajah mereka.
2. Evaluasi Performa Sistem:
    Performa sistem akan dievaluasi dengan mengukur sejauh mana sistem dapat mendeteksi dan mencocokkan wajah karyawan dengan akurasi yang tinggi. Metrik evaluasi seperti akurasi pengenalan, 
   presisi, recall, dan F1-score akan digunakan untuk mengukur performa sistem.
3. Analisis Data Hasil:
    Hasil pengujian dan evaluasi akan dianalisis untuk memahami performa sistem. Jika ditemukan masalah atau area untuk perbaikan, analisis ini akan membantu dalam mengidentifikasi solusi yang 
   tepat.

3.5.6. Analisis Data dan Hasil
Pada tahap analisis data dan hasil, penelitian akan melibatkan langkah-langkah berikut:

1. Analisis Data Hasil Pengujian:
    Data hasil pengujian, yang mencakup hasil pengenalan wajah karyawan, akan dianalisis. Ini mencakup akurasi pengenalan, tingkat kesalahan (misidentification), dan performa sistem dalam 
   situasi kehadiran yang berbeda.
2. Interpretasi Hasil Pengenalan Wajah:
    Hasil pengenalan wajah akan diinterpretasikan untuk memahami sejauh mana sistem dapat mengenali wajah karyawan dengan benar. Ini mencakup identifikasi individu karyawan, pencatatan waktu 
   kehadiran, dan pencocokan dengan data informasi karyawan yang bersangkutan.
3. Evaluasi Tingkat Akurasi Sistem:
     Akurasi sistem dalam pengenalan wajah akan dievaluasi dengan menggunakan metrik evaluasi yang sesuai. Ini akan membantu dalam mengukur sejauh mana sistem berhasil memenuhi tujuannya.

3.5.7. Penyusunan Laporan
Setelah analisis data dan hasil selesai, langkah terakhir adalah menyusun laporan akhir. Laporan ini akan mencakup:

1. Hasil penelitian, termasuk akurasi pengenalan wajah dan performa sistem.
2. Kesimpulan dari penelitian, yang akan merangkum hasil dan temuan penting.
3. Saran untuk pengembangan sistem Live Attendance di PT. Setia Kawan Makmur Sejahtera. Saran ini dapat mencakup perbaikan sistem, pengoptimalan, atau penggunaan lebih lanjut dari teknologi pengenalan wajah.

3.6. Etika Penelitian
Penelitian ini akan mematuhi prinsip-prinsip etika yang ketat, termasuk privasi dan keamanan data karyawan yang terlibat dalam penelitian. Langkah-langkah etika meliputi:

1. Perlindungan Privasi:
    Data wajah karyawan akan diolah dan disimpan dengan menjaga kerahasiaan. Identitas karyawan akan dilindungi, dan data hanya akan digunakan untuk tujuan penelitian.
2. Kepatuhan Regulasi Privasi:
    Penelitian akan dilakukan sesuai dengan regulasi privasi yang berlaku, seperti Peraturan Perlindungan Data Pribadi (GDPR) jika berlaku.
3. Izin dan Persetujuan:
    Jika diperlukan, izin dan persetujuan dari karyawan yang terlibat dalam penelitian akan diperoleh sebelum pengambilan gambar wajah.

3.7. Jadwal Penelitian
Penelitian ini akan dilakukan selama periode waktu bulan Agustus hingga Desember. Jadwal penelitian akan mencakup semua tahap yang telah dijelaskan dalam tahap penelitian (3.5). Jadwal ini akan memastikan kelancaran penelitian dan implementasi sistem Live Attendance.

Metodologi penelitian ini akan memandu langkah-langkah yang akan diambil dalam pengembangan Sistem Live Attendance dengan Teknologi Pengenalan Wajah menggunakan CNN di PT. Setia Kawan Makmur Sejahtera. Langkah-langkah ini akan memungkinkan evaluasi efektivitas sistem dalam memantau kehadiran karyawan dan memberikan manfaat bagi perusahaan.
