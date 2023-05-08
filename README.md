# BinaryLogisticRegressionWithRidgeRegularization
Repository ini berisi Dataset dengan nama Ad.CSV dengan File IPYNB Python kode untuk memodelkan regresi logistik Biner dengan regularisasi ridge

## Dataset
Dataset yang digunakan merupakan data advertising yang didapatkan dari kagle dengan variabel sebagai berikut
1. Daily Time Spent on Site,
2. Daily Time Spent on Apps,
3. Age,
4. Area Income,
5. Ad Topic Line,
6. City,
7. Gender,
8. Country,
9. Timestamp,
10. Clicked on Ad.

## Penyesuaian
Penulis melakukan beberapa penyesuaian agar dataset agar data memiliki masalah yang lebih kompleks dan dapat diolah dengan langkah-langkah yg lebih lengkap sebagai simulasi pengolahan dan permodelan, yaitu.
1. Penulis menahbahkan variabel Daily Time Spent on Apps yang berkolerasi dengan variabel Daily Time Spent on Site agar muncuk gejala multikolinearitas,
2. Penulis menghapus beberapa value pada variabel Area Income agar terdapat missing value,
3. Penulis menghapus beberapa unit observasi agar data menjadi imbalance,
4. Penulis merubah variabel Gender yang sebelumnya sudah berupa encode 0,1 menjadi kategorikal "Male","Female.

# Refrensi
* [Dataset Awal](https://www.kaggle.com/code/alyeasin/click-on-ad/input)
