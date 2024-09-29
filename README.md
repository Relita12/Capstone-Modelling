# Capstone-Modelling
## Background
Daegu adalah salah satu kota yang padat penduduknya di Korea Selatan. Kota ini juga memiliki industry dan tempat wisata/hiburan yang banyak. Oleh karena itu lahan di daegu semakin menipis dan ini menjadi sebuah peluang bisnis yang bagus untuk menyediakan hunian yang hemat lahan seperti Apartment

## Problem Statement
Penentuan harga jual apartment menjadi challenging karena Perusahaan real estate menggunkan berbagai strategi agar demand dan profit tetap seimbang. Apabila harga terlalu tinggi demand akan menurun dan apabila harga terlalu renda maka profit Perusahaan akan menurun

## Goals
perusahaan agen real estate dapat menentukan harga yang kompetitif dengan apartment dan fasilitas yang ditawarkan. Dan juga, perusahaan dapat mengetahui apa/faktor/variabel apa yang membuat konsumen tertari menyewa/membeli apartment.

 ## Metrics Evaluation
![image](https://github.com/user-attachments/assets/9a98be6d-8385-4b2c-833a-5d092b2231c6)

## Variabel
|kolom | Penjelasan |
|---- | ---- |
| HallwayType | Tipe Apartment|
| TimeToSubway | Waktu yang dibutuhkan ke subway terdekat dari Apartment|
| SubwayStation | Stasiun Subway terdekat dari Apartment |
| N_FacilitiesNearBy(ETC) | Jumlah fasilitas di sekitar Apartment |
| N_FacilitiesNearBy(PublicOffice) | Jumlah fasilitas kantor publik di sekitar Apartment |
| N_SchoolNearBy(University) | Jumlah universitas/kampus yang ada di dekat Apartment |
| N_Parkinglot(Basement) | Jumlah tempat parkir |
| YearBuilt | Tahun Apartment dibangun |
| N_FacilitiesInApt | Jumlah fasilitas yang ada di apartment |
| Size(sqft) | Luas Apartment (dalam square feet) |
| SalePrice | Harga Apartment (dalam Won) |

## Kesimpulan
1. Model terbaik yang diperoleh selama proses pemodelan untuk memprediksi harga sewa apartemen adalah modwl Gradient Boosting Regression menggunakan feature selection RFE dengan 5 fitur terbaik
2. Hyperparameter tidak digunakan karena hasil akurasi pada Gradient Boosting menggunakan feature selection RFE dengan 5 fitur terbaik masih lebih baik
3. Akurasi nya yang diperoleh dari best model menggunakan MAE 36.685 won
4. Fitur yang paling berpengaruh terhadap harga apartemen di Daegu adalah Hallway Type Mixed
5. Keuntungan nya menggunakan ML sebanyak 77.037 won
![image](https://github.com/user-attachments/assets/05b0aac8-4b5e-4ddf-9238-1a58e68b5e54)





