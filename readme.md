BookGenie: Sistem Rekomendasi Buku menggunakan Artificial Intelligence
BookGenie adalah sistem rekomendasi buku berbasis Artificial Intelligence yang menggabungkan analisis kepribadian psikologis (Big Five Personality Traits) dengan teknik machine learning untuk memberikan rekomendasi buku yang hiper-personalisasi. Aplikasi ini dirancang untuk membantu pengguna menemukan buku yang tidak hanya sesuai dengan minat mereka, tetapi juga selaras dengan tipe kepribadian mereka, sehingga meningkatkan kepuasan membaca dan keterlibatan pengguna (engagement).

Fitur Utama:
1. Kuesioner Kepribadian Singkat : mengukur 5 dimensi kepribadian (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism).Menggunakan 10 pertanyaan dengan validitas psikometrik yang tinggi.

2. Sistem Rekomendasi Hybrid AI yang menggabungkan: Knowledge-Based Filtering (berdasarkan genre, penulis, penerbit), dan Content-Based Filtering (analisis kecocokan buku dengan kepribadian pengguna).

Alasan BookGenie dibuat :
1. Kesulitan Memilih Buku
a. 65% pembaca menghabiskan waktu >30 menit untuk memilih buku (World Literacy Foundation, 2023).
b. 34% tidak membeli buku karena kebingungan (Perpustakaan Nasional, 2022).

2. Keterbatasan Sistem Rekomendasi Konvensional
a. Rekomendasi berbasis popularitas atau kategori umum tidak mempertimbangkan faktor psikologis.
b. Studi Guan et al. (2020) menunjukkan sistem tanpa analisis kepribadian memiliki akurasi 30% lebih rendah.

3. Kebutuhan Personalisasi Mendalam
a. Kepribadian memengaruhi preferensi bacaan (Tkalčič et al., 2013). Contoh: Orang dengan Openness tinggi cenderung menyukai fiksi ilmiah/fantasi, sedangkan orang dengan Conscientiousness tinggi lebih memilih buku pengembangan diri.

Tujuan : Mengurangi decision fatigue dengan rekomendasi personalisasi, dan meningkatkan kebiasaan membaca berkelanjutan.

Manfaat : Menghemat waktu pemilihan buku, pengalaman membaca lebih memuaskan, dan meningkatkan minat baca jangka panjang.

Validasi Big Five Personality dalam BookGenie
1. Reliabilitas Tinggi
a. Meta-analisis Barrick & Mount (2016) menunjukkan α = 0.85–0.90 untuk pengukuran Big Five.
b. Kuesioner singkat (3 item per trait) tetap valid (α = 0.75–0.82) (Gosling dkk., 2017).

Korelasi dengan Preferensi Buku
a. Openness. Skor tinggi suka fiksi ilmiah (r=0.47), fantasi, dan puisi, sedangkan skor rendah lebih ke non-fiksi praktis.
b. Conscientiousness. Skor tinggi cenderung baca buku pengembangan diri (r=0.41) dan bisnis, sedangkan skor rendah lebih ke bacaan santai.
c. Extraversion. Skor tinggi tertarik biografi (r=0.42) dan buku sosial, sedangkan skor rendah lebih suka novel kompleks.
d. Agreeableness. Skor tinggi pilih romansa (r=0.44) dan kisah inspiratif, sedangkan skor rendah lebih ke thriller.
e. Neuroticism. Skor tinggi cari buku escapist (r=0.38) dan self-help, sedangkan skor rendah lebih suka tema gelap.

-> Semua korelasi didukung penelitian empiris (Tkalčič et al., 2013 dan Youyou et al., 2020).

Alur Kerja Sistem
1. Pengisian Kuesioner Kepribadian
a. Pengguna menjawab 10 pertanyaan singkat untuk mengidentifikasi Big Five Traits.
b. Hasilnya dinormalisasi dalam skala 0-1.

2. Analisis AI untuk Rekomendasi
a. Knowledge-Based Filtering: Memfilter buku berdasarkan genre/penulis.
b. Content-Based Filtering (analisis kecocokan buku dengan kepribadian pengguna).

3. Penampilan Rekomendasi
a. Setiap buku ditampilkan dengan persentase kecocokan kepribadian (contoh: Openness 85%).
b. Deskripsi buku.

