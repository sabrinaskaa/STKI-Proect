# Sistem Temu Kembali Informasi (STKI)

## Daftar Eksperimen
### Minggu 2 — *Document Preprocessing & Word Frequency*
**Tahapan:**
- Membaca teks berita dari file `.json`
- Membersihkan teks (hapus angka, tanda baca, huruf besar)
- Tokenisasi dan filtering kata
- Menghitung frekuensi kemunculan kata (Word Frequency)
- Visualisasi hasil dalam bentuk grafik batang

### Minggu 3 — *Boolean Model Implementation*
**Tahapan:**
- Preprocessing teks dari beberapa file `.txt`
- Membentuk struktur *Inverted Index*  
- Menampilkan *Incidence Matrix* antar term dan dokumen  
- Implementasi pencarian query Boolean (AND, OR, NOT)
- Visualisasi hasil menggunakan pandas DataFrame


### Minggu 4 — *Vector Space Model (Bag of Words & TF-IDF)*
**Tahapan:**
- Membaca dataset `.csv`
- Representasi teks menggunakan *CountVectorizer* dan *TfidfVectorizer*
- Analisis distribusi kata dan label
- Eksperimen *n-gram (unigram, bigram)*
- Visualisasi WordCloud
- Perhitungan kemiripan antar dokumen menggunakan *Cosine Similarity*

### Minggu 8 — *Klasifikasi Text Mining Naive Bayes*
**Tahapan:**
- Membaca dataset `.csv`
- Preprocessing teks *(case folding, tokenisasi, dan penghapusan stopwords)*
- Bag of Words dengan CountVectorizer
- Pemodelan *Naive Bayes*
- Prediksi dan evaluasi

### Minggu 9 — *Klasifikasi Text Mining NB dan KNN*
**Tahapan:**
- Membaca dataset `.csv`
- Preprocessing teks *(case folding, tokenisasi, dan penghapusan stopwords)*
- TF-IDF dengan TfidfVectorizer
- Membangun pipeline klasifikasi
- Klasifikasi dengan *Naive Bayes*
- Klasifikasi menggunakan *K-Nearest Neighbor (KNN)*
- Evaluasi dan perbandingan model

### Minggu 10 — *Document Clustering*
**Tahapan:**
- Membaca dataset `.csv`
- Preprocessing teks *(case folding, tokenisasi, dan penghapusan stopwords)*
- TF-IDF dengan TfidfVectorizer
- Clustering dokumen menggunakan algoritma *K-Means*
- Penentuan jumlah cluster
- Analisis hasil clustering
- Interpretasi cluster

### Minggu 11 — *Summarization*
**Tahapan:**
- Membaca dataset `.csv`
- Preprocessing teks *(case folding, tokenisasi, dan penghapusan stopwords)*
- Representasi teks
- Perhitungan bobot kata/kalimat
- Pemilihan kalimat penting
- Pembentukan ringkasan
