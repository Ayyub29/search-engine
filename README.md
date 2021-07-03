# Search Engine: Extended Version
Versi Selasa, 7 Juli 2021

## Latar Belakang
Semester 3 yang lalu, kalian sudah berhasil membangun sebuah Search Engine sederhana berbasis Cosinus Similarity. Tentu Search Engine tersebut adalah bentuk search engine yang sudah disimplifikasi dari Search Engine yang sesungguhnya. Oleh karena itu, pada proyek ini, kami menantang kalian Ca-IRK 2019 untuk membangun sebuah search engine yang lebih advanced dan mendekati dengan search engine yang sesungguhnya.
<p align="center">
<img src="https://qwords.com/blog/wp-content/uploads/2019/10/Google-logo-Qwords-by-Andy-N.png" height="300" width="500"></p>
<p align="center"><i>Gambar 1. Tampilan Google sebagai Search Engine</i></p>

## Deskripsi Tugas
Pada kesempatan ini, kalian akan membangun sebuah Search Engine yang lebih kompleks dengan memanfaatkan beberapa algoritma lain pendukung search engine dalam mengambil dokumen dan menampilkan hasil pencarian berdasarkan kata kunci yang dimasukkan. Search Engine ini akan dibagi ke dalam tiga milestone berbeda, yaitu:
1. Implementasi Heap Sort untuk Pengurutan
2. Penerapan Algoritma TF-IDF dalam Search Engine
3. Menampilkan Relevansi dan Ranking Pencarian dengan Page Rank Algorithm
<br><br>
### **Milestone 1: Implementasi Heap Sort untuk Pengurutan (650 poin)**
Pengurutan (sorting) menjadi faktor terpenting dalam menampilkan urutan website berdasarkan relevansi tertinggi. Dahulu kalian sudah mempelajari berbagai jenis sorting seperti Bubble Sort, Quick Sort, Merge Sort, Insertion Sort, dan Selection Sort. Pada kesempatan ini, kalian kami tantang untuk membangun sebuah sorting jenis lain yang disebut sebagai Heap Sort. Buat juga analisis terkait Heapsort serta kelebihan dan kekurangannya dalam sebuah file README. Khusus bagian ini, Anda diwajibkan pula untuk membuat **Unit Testing** sederhana untuk melakukan pengujian terhadap Heap Sort yang kalian bangun.
<br><br>
### **Milestone 2: Penerapan Algoritma TF-IDF dalam Search Engine (1300 poin)**
Penerapan Cosine Similarity pada Tubes Aljabar dan Geometri sebelumnya memiliki beberapa kekurangan. Pada tugas kali ini, kami tantang kalian untuk mengimplementasikan pembentukan vektor dengan TF-IDF terlebih dahulu sebelum menerapkan Cosine Similarity. Buat juga analisis terkait Algoritma TF-IDF serta kelebihan dan kekurangannya dalam sebuah file README.
<br><br>
### **Milestone 3: Menampilkan Relevansi dan Ranking Pencarian dengan Page Rank Algorithm (1300 poin)**
Penerapan TF-IDF dalam Search Engine masih juga belum cukup. Untuk itu, dibutuhkan _second metric_ untuk membantu mengatasi kelemahan tersebut. Untuk itu, kami tantang kalian untuk mengimplementasikan PageRank Algorithm, algoritma yang ditemukan oleh Larry Page untuk Google. Penerapan kombinasi antara TF-IDF dan PageRank Algorithm dibebaskan, namun jelaskan alasannya dalam sebuah file README. Buat juga analisis terkait PageRank Algorithm serta Kelebihan dan Kekurangannya dalam file README yang sama.

## Bonus
Catatan: Bonus hanya akan dinilai apabila ketiga milestone di atas sudah diselesaikan dengan baik.
1. Dokumen-dokumen yang diperoleh dilakukan dengan teknik Web Scraping. (200 poin)
2. Search Engine dalam jumlah yang besar dengan pengambilan lebih dari 100 dokumen. Anda tentu membutuhkan script atau automation tertentu untuk menunjang kebutuhan ini. Untuk pemodelan referensi pada Page Rank dibebaskan metodenya. (650 poin)

## Spesifikasi Program
1. Program yang dibangun merupakan aplikasi berbasis web menggunakan bahasa Golang (GO). Bahasa ini menjadi tren zaman sekarang, khususnya dalam membangun back end dari sebuah website.
2. Seluruh algoritma dibangun dari *scratch* tanpa menggunakan library apapun. Segala bentuk fungsi dikemas tersendiri. Library yang diperbolehkan hanya library untuk pembuatan tampilan website (Front End).
3. Segala struktur data, fungsi, dan lain-lain dibuat semodular mungkin. Semakin modular, maka program yang kalian bangun akan lebih mudah untuk dilakukan proses debugging.
4. Penyimpanan dokumen-dokumen search engine dibebaskan sesuai dengan kreativitas kalian. 
5. Terdapat 4 README: Readme Utama yang mengikuti template berikut https://github.com/othneildrew/Best-README-Template, serta Readme untuk setiap Milestone.

## Pengerjaan Tugas
* Buatlah repositori baru (*private*) lalu invite akun GitHub **Ayyub29** dan **michaellhans**
* Penilaian Tugas dilakukan dengan melakukan demo secara langsung menggunakan Google Meet dengan terlebih dahulu menghubungi salah satu asisten untuk penjadwalan demo.
* Bila ada pertanyaan, silakan bertanya langsung ke asisten via LINE Group GAPADAT(K) agar dapat dicermati oleh seluruh calon asisten. 

## Pesan
Selamat mengerjakan! It's not worth it if you are not having fun!