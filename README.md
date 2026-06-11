# Pengolahan-Citra-Citra-Digital

Nama : Afnan Dika Ramadhan

NIM: 312410518

# Tugas 1

![foto](https://github.com/nanafnan09/Pengolahan-Citra-Citra-Digital/blob/c76af7314acea8239c528b06573154418cabea0d/Cuplikan%20layar%202026-06-11%20231012.png)

Mendeteksi orang jalan di sekitar


# Tugas 2

![foto](https://github.com/nanafnan09/Pengolahan-Citra-Citra-Digital/blob/c76af7314acea8239c528b06573154418cabea0d/Cuplikan%20layar%202026-06-11%20232421.png)

Foto Mobil yang ingin di deteksi

![foto](https://github.com/nanafnan09/Pengolahan-Citra-Citra-Digital/blob/c76af7314acea8239c528b06573154418cabea0d/Cuplikan%20layar%202026-06-11%20232652.png)

Output dari mendeteksi plat mobil

# Tugas 3

1. PendahuluanMendeteksi manusia di dalam gambar adalah tugas yang menantang karena penampilan mereka yang bervariasi serta berbagai macam pose yang bisa mereka lakukan. Kebutuhan utamanya adalah sebuah set fitur yang tangguh, yang memungkinkan bentuk manusia dibedakan dengan jelas, bahkan pada latar belakang yang rumit di bawah kondisi pencahayaan yang sulit.  Kami mempelajari masalah set fitur untuk deteksi manusia, dan menunjukkan bahwa deskriptor Histogram of Oriented Gradient (HOG) yang dinormalisasi secara lokal memberikan kinerja yang sangat baik dibandingkan dengan set fitur lain yang sudah ada, termasuk wavelets. Deskriptor yang kami usulkan ini mirip dengan histogram orientasi tepi, deskriptor SIFT, dan shape contexts, tetapi deskriptor kami dihitung pada grid yang rapat dari sel-sel yang berjarak seragam, serta menggunakan normalisasi kontras lokal yang saling tumpang tindih untuk meningkatkan kinerjanya.  Kami melakukan studi terperinci mengenai efek dari berbagai pilihan implementasi terhadap kinerja detektor, dengan mengambil "deteksi pejalan kaki" (deteksi orang yang sebagian besar terlihat dalam pose kurang lebih tegak) sebagai kasus ujinya. Untuk alasan kesederhanaan dan kecepatan, kami menggunakan SVM linear sebagai pengklasifikasi dasar (baseline classifier) di sepanjang studi ini.  Detektor baru ini memberikan hasil yang pada dasarnya sempurna pada set pengujian pejalan kaki dari MIT, sehingga kami telah membuat set data baru yang lebih menantang yang berisi lebih dari 1800 gambar pejalan kaki dengan rentang pose dan latar belakang yang sangat bervariasi. Pekerjaan yang sedang kami kembangkan saat ini juga menunjukkan bahwa set fitur kami berkinerja sama baiknya untuk mengenali kelas objek berbasis bentuk lainnya.
