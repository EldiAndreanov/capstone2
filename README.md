Judul : Customer retention analysis
Target
•	Dewan Direksi
•	Direktur Utama
•	Manajer pemasaran
•	Tim analitik bisnis
Visi Misi perusahaan
	Visi
•	Menciptakan pengalaman belanja yang menyenangkan dan mudah, di mana pelanggan selalu menemukan produk segar dan berkualitas tinggi dengan nilai terbaik.
•	Menjadi bagian penting dari komunitas, mendukung keluarga dan gaya hidup sehat melalui produk dan layanan kami.
•	Menjadi pilihan utama untuk kebutuhan sehari-hari, menginspirasi pelanggan dengan pilihan makanan baru dan menarik serta suasana yang ramah.
Misi
•	Menyediakan beragam pilihan bahan makanan segar, berkualitas tinggi, dan kebutuhan rumah tangga dengan harga yang kompetitif, disertai pelayanan yang ramah dan efisien.
•	Menciptakan lingkungan belanja yang bersih, teratur, dan nyaman untuk pengalaman berbelanja yang menyenangkan.
•	Terus meningkatkan operasional dan penawaran kami untuk memenuhi kebutuhan dan preferensi pelanggan yang terus berubah.
Latar Belakang
	Dalam lingkungan bisnis supermarket yang kompetitif, pemahaman yang mendalam tentang perilaku pelanggan adalah kunci untuk pertumbuhan dan keberlanjutan. Salah satu metrik terpenting saat menganalisis perilaku pelanggan adalah LRFM data. Yang memiliki makna ketika seorang pelanggan melakukan pembelian terakhir. Analisis terkini memberikan pengetahuan yang berharga tentang partisipasi pelanggan, loyalitas dan tingkat potensi risiko kehilangan pelanggan. 
Laporan ini dimaksudkan untuk menganalisis data LRFM pelanggan untuk mengidentifikasi segmen pelanggan berdasarkan bagaimana mereka dibeli. Pemahaman ini memungkinkan supermarket untuk mengembangkan strategi pemasaran dan penyimpanan yang lebih efektif dan terarah, meningkatkan loyalitas pelanggan dan mengoptimalkan alokasi sumber daya.
Flow Analisis
1.	Mengecek apakah ada data yang dibutuhkan null atau tidak. Jika ada, tentukan untuk dibuang atau diisi dengan value yang tepat.
Expected output: data yang lengkap dan bisa digunakan. 
2.	Mengecek, apakah distribusi data recency normal atau tidak?
Expected output: histogram data recency terdistribusi normal
3.	Membuat kolom monetary, length, dan frequency, kemudian jadikan satu dalam suatu dataframe baru yang berisi “Length, Recency, Frequency, Monetary”.
Expected output: Dataframe baru berupa LRFM
4.	Buat segmentasi menggunakan K-Means, buat scoring setiap kolom LRFM.
5.	Analisis Segmentasi (jumlah masing-masing segmentasinya, dll)
Solusi:
1.	Membuat campaign khusus agar customers yang tidak aktif bisa tertarik membeli lagi. (Campaign yang paling cocok adalah pemberian hadiah pada setiap pembelian secara berturut-turut dengan jumlah dan waktu yang sudah ditetapkan – contoh ‘pemberian kupon untuk mendapatkan doorprise hadiah dalam 2 bulan kedepan dengan jumlah pembelian minimal 100$’)
2.	Memberikan hadiah kepada customers yang sangat aktif untuk menjaga loyalitas.
