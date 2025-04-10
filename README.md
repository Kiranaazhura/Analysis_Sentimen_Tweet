# Analisis Sentimen Layanan Provider Seluler Indonesia

## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan **analisis sentimen** terhadap tweet yang berkaitan dengan **penyedia layanan seluler**. Dengan menggunakan teknik *Natural Language Processing (NLP)*, proyek ini mengklasifikasikan tweet ke dalam kategori sentimen seperti **positif**, **negatif**, dan **netral** untuk memahami persepsi publik terhadap layanan yang diberikan.

---

## Dataset

- **Sumber**: `dataset_tweet_sentiment_cellular_service_provider.csv`
- **Isi**: Kumpulan tweet dari pelanggan yang menyampaikan opini terhadap penyedia layanan seluler.
- **Label**: Setiap tweet telah dilabeli dengan kategori sentimen.

---

## Metodologi

1. **Pra-pemrosesan Data**:
   - Mengubah teks menjadi huruf kecil (lowercase).
   - Menghapus URL, mention, angka, tanda baca, dan karakter khusus.
   - Menghapus stopword dengan menggunakan kamus khusus (`StopWords_Tala.csv`).

2. **Tokenisasi**
   - Tokenisasi menggunakan NLTK.

3. **Analisis Distribusi Sentimen**:
   - Visualisasi dengan diagram pie untuk melihat proporsi sentimen.

---

## Hasil

- Distribusi sentimen menunjukkan bagaimana persepsi umum pelanggan terhadap penyedia layanan.
- Sentimen negatif umumnya berkaitan dengan masalah seperti jaringan lambat, layanan buruk, atau pengalaman negatif lainnya.
