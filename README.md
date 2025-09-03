# Implementasi_Algoritma_SVM_untuk_Analisis_Sentimen_Ulasan_Aplikasi_DeepSeek
Author: Abel Levran
Proyek ini berfokus pada analisis sentimen terhadap data yang terkait dengan AI DeepSeek, Generative AI yang bersaing dengan ChatGPT & Meta. Tujuan utama proyek ini adalah mengklasifikasikan sentimen (positif dan negatif) dari ulasan pengguna aplikasi DeepSeek, menggunakan berbagai teknik pembelajaran mesin.

##The notebook (sentiment-analysis.ipynb) berisi beberapa bagian utama:
1. Ekstraksi Data: Data diekstraksi menggunakan perpustakaan google-play-scraper, dengan fokus pada ulasan pengguna dari Google Play Store. Bagian ini menangani pengumpulan data yang relevan untuk analisis sentimen.
2. Data Preprocessing: Termasuk langkah-langkah seperti pembersihan teks, tokenisasi, dan pengkodean label sentimen untuk mempersiapkan data mentah untuk analisis.
3. Ekstraksi Fitur: TF-IDF - Mengonversi data teks menjadi fitur numerik untuk model pembelajaran mesin.
4. Model Training and Evaluation: Menerapkan dan mengevaluasi beberapa model pembelajaran mesin: model SVM sebagai yg utama dan K-NN dan Naive Bayes sebagai pembanding menggunakan TF-IDF.
5. Inferensi dan Output: Melakukan inferensi pada data uji dan menghasilkan label sentimen kategorikal (misalnya, positif dan negatif) serta memvisualisasikan frekuensi kata yang paling banyak muncul dari setiap kategori
