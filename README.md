## UTS Pengolahan Citra Digital Menggunakan Algoritma SVM
Support Vector Machine (SVM) adalah algoritma supervised machine learning yang powerful dan dapat digunakan untuk masalah klasifikasi maupun regresi. Namun, SVM lebih dikenal dan lebih sering digunakan untuk tugas klasifikasi.

Tujuan utama SVM adalah menemukan hyperplane (garis pemisah) terbaik dalam ruang berdimensi tinggi (high-dimensional space) yang secara jelas memisahkan titik-titik data dari kelas yang berbeda.

Konsep Kunci SVM
Untuk memahami SVM, ada tiga konsep inti:

1. Hyperplane
Ini adalah "garis" pemisah.

Jika data Anda 2 dimensi (2D), hyperplane adalah garis lurus.

Jika data Anda 3 dimensi (3D), hyperplane adalah bidang datar.

Jika data Anda lebih dari 3 dimensi, secara matematis disebut hyperplane.

Tugas SVM adalah mencari hyperplane yang optimal.

2. Maximum Margin (Margin Maksimal)
"Hyperplane terbaik" adalah hyperplane yang memiliki margin (jarak) terbesar antara dirinya dengan titik data terdekat dari masing-masing kelas.

Margin adalah jarak tegak lurus dari hyperplane ke titik data terdekat.

SVM berusaha memaksimalkan margin ini. Dengan margin yang lebar, model SVM menjadi lebih robust (kuat) dan memiliki kemampuan generalisasi yang lebih baik untuk menebak data baru.

3. Support Vectors (Vektor Pendukung)
Ini adalah titik-titik data yang posisinya paling dekat dengan hyperplane; mereka adalah titik-titik yang "menopang" atau "mendukung" margin.

Hanya support vectors inilah yang memengaruhi posisi dan orientasi hyperplane. Jika titik data lain (yang bukan support vector) digeser atau dihapus, hyperplane tidak akan berubah. Inilah yang membuat SVM efisien secara komputasi.

https://drive.google.com/drive/folders/10My06m4CN1RnzjPivwItplztqJ1Llu3u?usp=sharing

| No | Keterangan | Gambar |
|----|-------------|--------|
| 1  | Daun Nangka | ![Images](result/daunnangka.png) |
| 2  | Daun Sirih | ![Images](result/daunsirih.png) |# Uts_klasifikasi_daun_rafisuryaaudi
