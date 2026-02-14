**💸 Rupiah-Check**

Rupiah-Check adalah proyek Computer Vision berbasis Convolutional Neural Network (CNN) yang dibuat untuk mendeteksi uang kertas Rupiah dari gambar.


**🎯 Latar Belakang**

Proyek ini dibuat karena seorang teman ingin mengembangkan software yang dapat:

1. 📷 Mendeteksi nominal uang Rupiah dari kamera/gambar.

2. 🧑‍🎓 Setelah uang terdeteksi, sistem akan menjelaskan sejarah pahlawan nasional yang terdapat pada uang tersebut.

Jadi proyek ini bukan sekadar klasifikasi gambar, tetapi menjadi bagian dari sistem edukatif berbasis AI.


**🧠 Teknologi yang Digunakan**

1. Deep Learning

2. Convolutional Neural Network (CNN)

3. Data Augmentation

4. Callback Optimization:

   4.1 ReduceLROnPlateau

   4.2 EarlyStopping

5. Framework yang digunakan:

   5.1 Python

   5.2 TensorFlow / Keras


**🏗 Cara Kerja Model**

1. Dataset gambar uang Rupiah dikumpulkan dan diproses.

2. Data dibagi menjadi:

   2.1 Training set

   2.2 Validation set

   2.3 Test set

3. Model CNN dilatih untuk mengenali pola visual unik dari masing-masing nominal.

4. Setelah model mendeteksi nominal, sistem dapat menghubungkannya dengan informasi sejarah pahlawan pada uang tersebut.
   

**📊 Performa Model**

Validation Accuracy: ± 64%

Test Prediction: Cukup baik dalam mengenali nominal

Confidence model belum mencapai 90%

Meskipun akurasi validasi belum tinggi, model sudah menunjukkan kemampuan generalisasi yang cukup baik terhadap data uji.


**🔧 Teknik yang Digunakan untuk Meningkatkan Performa**
1️. Data Augmentation

Digunakan untuk memperkaya variasi data agar model lebih robust terhadap kondisi berbagai gambar.

2️. ReduceLROnPlateau

Menurunkan learning rate secara otomatis ketika performa validasi stagnan, agar model bisa melakukan fine tuning lebih baik.

3️. EarlyStopping

Menghentikan training lebih awal ketika model mulai overfitting.


**🚀 Potensi Pengembangan**

1. Beberapa peningkatan yang bisa dilakukan:

2. Menambah jumlah dataset

3. Menggunakan transfer learning (MobileNet, EfficientNet, dll)

4. Fine-tuning hyperparameter

5. Menambahkan preprocessing seperti background removal

6. Deployment ke aplikasi mobile atau web
   

**💡 Visi Proyek**

Rupiah-Check bukan hanya model klasifikasi, tetapi bagian dari sistem edukasi berbasis AI yang:

1. Membantu mengenali nominal uang

2. Mengedukasi masyarakat tentang sejarah pahlawan nasional

3. Dapat dikembangkan menjadi aplikasi pembelajaran interaktif
