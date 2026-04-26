- Judul Proyek:
  Skin Cancer Classification Using Hybrid CNN and MobileNetV2

Link Dataset:
https://www.kaggle.com/datasets/rm1000/skin-cancer-isic-images

- Deskripsi:
  Dataset Skin Cancer ISIC Images adalah dataset yang berisi kumpulan gamabar citra lesi kulit yang digunakan untuk mendeteksi potensi kanker kulit.Kemudian dataset ini terdiri dari 2 label Benign Dan Malignant

Model yang saya gunakan merupakan hybrid model yang menggabungkan transfer learning (MobileNetV2) dengan Convolutional Neural Network (CNN).Saya menggabungkan kedua arsitektur ini untuk memperkuat model agar mendapatkan hasil accuracy yang sesuai dengan kriteria (85%).

Struktur Model:
Input Layer (224×224×3)
data augmentation
MobileNetV2
Conv2D + MaxPooling
Conv2D + MaxPooling
GlobalAveragePooling
Dense Layer + Dropout
Output Layer (Sigmoid)

- Hasil Model
  Training Accuracy : 88.62%
  Validation Accuracy : 87.50%
  Test Accuracy : 85.14%

Hasil ini menunjukkan bahwa model hybrid (CNN & MobileNetV2) mampu melakukan klasifikasi gambar kanker kulit dengan akurasi lebih dari 85% pada data uji.
