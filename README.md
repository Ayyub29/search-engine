# Search Engine: Extended Version

# Latar Belakang
Semester 4 yang lalu, kalian sudah berhasil membangun sebuah Search Engine sederhana berbasis Cosinus Similarity. Tentu Search Engine tersebut adalah bentuk search engine simplifikasi sederhana dari Search Engine yang sesungguhnya. Oleh karena itu, pada proyek ini, kami menantang kalian Ca-IRK 2019 untuk membangun sebuah search engine yang lebih advanced dan mendekati dengan search engine yang sesungguhnya.

# Deskripsi Proyek
Pada kesempatan ini, kalian akan membangun sebuah Search Engine yang lebih kompleks dengan memanfaatkan beberapa algoritma lain pendukung search engine dalam mengambil dokumen dan menampilkan hasil pencarian berdasarkan kata kunci yang dimasukkan. Search Engine ini akan dibagi ke dalam tiga milestone berbeda, yaitu:
1. Implementasi Heap Sort
2. Penerapan Algoritma TF-IDF dalam Search Engine
3. Menampilkan Relevansi dan Ranking Pencarian dengan Page Rank Algorithm

## Milestone 1: Implementasi Heap Sort untuk Pengurutan (750 poin)
Pengurutan (sorting) menjadi faktor terpenting dalam menampilkan urutan website berdasarkan relevansi tertinggi. Dahulu kalian sudah mempelajari berbagai jenis sorting seperti Bubble Sort, Quick Sort, Merge Sort, Insertion Sort, dan Selection Sort. Pada kesempatan ini, kalian kami tantang membangun sebuah sorting jenis lain yang disebut sebagai Heap Sort. Buat juga analisis terkait Heapsort serta kelebihan dan kekurangannya dalam sebuah file README.

## Milestone 2: Penerapan Algoritma TF-IDF dalam Search Engine (1250 poin)
Penerapan Cosine Similarity pada Tubes Aljabar dan Geometri sebelumnya memiliki beberapa kekurangan. Pada tugas kali ini, kami tantang kalian untuk mengimplementasikan pembuntakn vektor dengan TF-IDF terlebih dahulu sebelum menerapkan Cosine Similarity. Buat juga analisis terkait Algoritma TF-IDF serta Kelebihan dan Kekurangannya dalam sebuah file README.

## Milestone 3: Menampilkan Relevansi dan Ranking Pencarian dengan Page Rank Algorithm (1250 poin)
Penerapan TF-IDF dalam Search Engine masih memiliki beberapa kekurangan. Untuk itu, dibutuhkan _second metric_ untuk membantu mengatasi kelemahan tersebut. Untuk itu, kami tantang kalian untuk mengimplementasikan PageRank Algorithm, algoritma yang ditemukan oleh Larry Page untuk Google. Penerapan kombinasi antara TF-IDF dan PageRank Algorithm dibebaskan, namun jelaskan alasannya dalam sebuah file README. Buat juga analisis terkait PageRank Algorithm serta Kelebihan dan Kekurangannya dalam file README yang sama.

## Bonus
1. Dokumen-dokumen yang diperoleh dilakukan dengan teknik Web Scraping. (100 poin, Prereq: Milestone 2)
2. Search Engine dalam jumlah yang besar dengan pengambilan lebih dari 100 dokumen. Anda tentu membutuhkan script atau automation tertentu untuk menunjang kebutuhan ini. Untuk pemodelan referensi pada Page Rank dibebaskan metodenya. (600 poin, Prereq: Milestone 2)
3. Tuliskan alasan masuk IRK serta ingin menjadi asisten untuk matkul apa saja beserta alasan dalam README utama. (0.5 Poin/Kata, Maks 150 Poin, Prereq: Milestone 3)

# Spesifikasi Program
1. Program yang dibangun merupakan aplikasi berbasis web menggunakan bahasa Golang (GO). Bahasa ini menjadi tren zaman sekarang, khususnya dalam membangun back end dari sebuah website.
2. Seluruh algoritma dibangun dari *scratch* tanpa menggunakan library apapun. Segala bentuk fungsi dikemas tersendiri. Library yang diperbolehkan hanya library untuk pembuatan tampilan website (Front End).
3. Segala struktur data, fungsi, dan lain-lain dibuat semodular mungkin. Semakin modular, maka program yang kalian bangun akan lebih mudah untuk dilakukan proses debugging.
4. Penyimpanan dokumen-dokumen search engine dibebaskan sesuai dengan kreativitas kalian. 
5. Terdapat 4 README: Readme Utama yang mengikuti template berikut https://github.com/othneildrew/Best-README-Template, serta Readme untuk setiap Milestone.

# Pengumpulan Tugas
Pengumpulan Tugas dilakukan dengan melakukan forking terhadap repository ini dan mengcontact salah satu asisten.

# Pesan
Selamat mengerjakan! It's not worth it if you are not having fun!
