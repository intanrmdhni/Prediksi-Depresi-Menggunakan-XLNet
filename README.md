# Prediksi-Depresi-Menggunakan-XLNet
Program yang dibangun untuk menyelesaikan kewajiban TA dengan judul Predicting Depressive Disorder Based on DASS-42 on Twitter Using XLNet's Pretrained Model Classification Text

Twitter adalah situs media sosial gratis yang tidak hanya menjadi tempat untuk berbagi postingan dan konten
multimedia tetapi juga menawarkan penggunanya untuk mengekspresikan perasaan, emosi, dan sentimen mereka
tentang suatu isu. Maka dengan hal tersebut, sering ditemukan pengguna Twitter membuat postingan yang
menunjukkan bagaimana perilaku pengguna tersebut termasuk masalah mental yang dialami pengguna seperti gejala
depresi, kecemasan, dan gangguan stres. Hanya sekitar setengah dari kasus depresi yang dapat dideteksi oleh dokter
atau ahli lainnya, hal ini dikarenakan sampai saat ini, diagnosis depresi dimulai dari laporan pasien, keluarga, atau
teman dekat pasien, atau juga dimulai dari hasil tes tertentu seperti kuesioner. Maka penelitian ini membangun
model untuk memprediksi depresi dengan membangun model yang memprediksi apakah seseorang mengalami
depresi melalui tweet di Twitter menggunakan model klasifikasi teks XLNet pre-trained. Pengujian dilakukan
dengan menghilangkan stemming dari tahap preprocessing. Pengujian juga dilakukan dengan menambahkan
hyperparameter untuk fine-tuning model XLNet. Pengujian juga dilakukan dengan menggunakan dataset yang
menyaring kata asing dimana data asing diterjemahkan ke dalam bahasa Indonesia. Data yang disimpan adalah data
yang menggunakan kata-kata berdasarkan kamus KBBI. Berdasarkan hasil pengujian model yang telah dilakukan
dengan menggunakan confusion matrix, model dapat memprediksi tweet yang berindikasi depresi dan mendapatkan
nilai akurasi sebesar 78,57%
