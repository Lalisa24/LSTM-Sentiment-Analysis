# LSTM-Sentiment-Analysis

Klasifikasi Teks Kesehatan Mental Menggunakan LSTM
Proyek ini bertujuan untuk membangun model Deep Learning yang mampu mengklasifikasikan pernyataan teks ke dalam berbagai kategori kondisi kesehatan mental. Dataset yang digunakan berisi lebih dari 50.000 entri yang mencakup berbagai kondisi psikologis.

📋 Ikhtisar Proyek
Model ini dilatih untuk mengenali pola bahasa yang terkait dengan beberapa kategori status kesehatan mental, antara lain:

Normal

Depression (Depresi)

Suicidal (Keinginan bunuh diri)

Anxiety (Kecemasan)

Bipolar

Stress

Personality Disorder (Gangguan Kepribadian)

🛠️ Fitur Utama
Analisis Data Eksploratif (EDA): Visualisasi distribusi kelas, statistik panjang teks, dan analisis frekuensi kata (word frequency).

Preprocessing Teks: Pembersihan teks (menghapus URL, simbol, angka), tokenisasi, normalisasi huruf kecil, dan penanganan nilai yang hilang/duplikat.

Arsitektur Deep Learning: Menggunakan model Long Short-Term Memory (LSTM) yang dibangun dengan TensorFlow/Keras untuk menangani data teks sekuensial secara efektif.

Evaluasi Model: Menggunakan metrik akurasi, classification report, dan confusion matrix untuk mengukur performa prediksi.

🚀 Teknologi yang Digunakan
Bahasa: Python

Libraries Utama: * Manipulasi Data: Pandas, NumPy

Visualisasi: Matplotlib, Seaborn

NLP & ML: NLTK, Scikit-learn

Deep Learning: TensorFlow, Keras

📊 Hasil Analisis Data
Berdasarkan eksplorasi data yang dilakukan:

Total data setelah pembersihan: ~51.074 baris.

Distribusi kelas menunjukkan kelas Normal dan Depression memiliki jumlah data terbanyak, sedangkan Personality Disorder adalah yang paling sedikit (minoritas).
