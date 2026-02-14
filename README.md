💸 Rupiah-Check

Rupiah-Check adalah proyek Computer Vision berbasis Convolutional Neural Network (CNN) yang dibuat untuk mendeteksi uang kertas Rupiah dari gambar.

🎯 Latar Belakang

Proyek ini dibuat karena seorang teman ingin mengembangkan software yang dapat:

📷 Mendeteksi nominal uang Rupiah dari kamera/gambar.

🧑‍🎓 Setelah uang terdeteksi, sistem akan menjelaskan sejarah pahlawan nasional yang terdapat pada uang tersebut.

Jadi proyek ini bukan sekadar klasifikasi gambar, tetapi menjadi bagian dari sistem edukatif berbasis AI.

🧠 Teknologi yang Digunakan

Deep Learning

Convolutional Neural Network (CNN)

Data Augmentation

Callback Optimization:

ReduceLROnPlateau

EarlyStopping

Framework yang digunakan:

Python

TensorFlow / Keras

🏗 Cara Kerja Model

Dataset gambar uang Rupiah dikumpulkan dan diproses.

Data dibagi menjadi:

Training set

Validation set

Test set

Model CNN dilatih untuk mengenali pola visual unik dari masing-masing nominal.

Setelah model mendeteksi nominal, sistem dapat menghubungkannya dengan informasi sejarah pahlawan pada uang tersebut.

📊 Performa Model

Validation Accuracy: ± 64%

Test Prediction: Cukup baik dalam mengenali nominal

Confidence model belum mencapai 90%

Meskipun akurasi validasi belum tinggi, model sudah menunjukkan kemampuan generalisasi yang cukup baik terhadap data uji.

🔧 Teknik yang Digunakan untuk Meningkatkan Performa
1️⃣ Data Augmentation

Digunakan untuk memperkaya variasi data agar model lebih robust terhadap:

Rotasi

Zoom

Perubahan pencahayaan

Flip

2️⃣ ReduceLROnPlateau

Menurunkan learning rate secara otomatis ketika performa validasi stagnan, agar model bisa melakukan fine tuning lebih baik.

3️⃣ EarlyStopping

Menghentikan training lebih awal ketika model mulai overfitting.

🚀 Potensi Pengembangan

Beberapa peningkatan yang bisa dilakukan:

Menambah jumlah dataset

Menggunakan transfer learning (MobileNet, EfficientNet, dll)

Fine-tuning hyperparameter

Menambahkan preprocessing seperti background removal

Deployment ke aplikasi mobile atau web

💡 Visi Proyek

Rupiah-Check bukan hanya model klasifikasi, tetapi bagian dari sistem edukasi berbasis AI yang:

Membantu mengenali nominal uang

Mengedukasi masyarakat tentang sejarah pahlawan nasional

Dapat dikembangkan menjadi aplikasi pembelajaran interaktif
