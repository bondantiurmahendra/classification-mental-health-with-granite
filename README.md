### **README.md**

# **Analisis Sentimen dan Klasifikasi Kesehatan Mental Menggunakan IBM Granite**

-----

### **Project Overview**

Proyek ini merupakan inisiatif untuk menganalisis dan mengklasifikasikan teks yang berkaitan dengan kesehatan mental. Dengan menggunakan model Large Language Model (LLM) IBM Granite, proyek ini bertujuan untuk mendeteksi sentimen dan mengidentifikasi kondisi kesehatan mental seperti Depresi, Stres, atau Kecemasan dari data teks tidak terstruktur. Output dari proyek ini adalah pemahaman mendalam tentang pola ekspresi emosi dan rekomendasi praktis untuk platform atau profesional di bidang kesehatan mental.

### **Raw Dataset Link**

Dataset yang digunakan dalam proyek ini adalah **"Sentiment Analysis for Mental Health"** yang tersedia secara publik di Kaggle.

Link: [https://www.kaggle.com/datasets/hasnainjaved/sentiment-analysis-for-mental-health](https://www.google.com/search?q=https://www.kaggle.com/datasets/hasnainjaved/sentiment-analysis-for-mental-health)

-----

### **Insight & Findings**

Berdasarkan analisis data, kami menemukan beberapa wawasan penting:

1.  **Dominasi Sentimen Stres dan Depresi**: Sebagian besar postingan yang dianalisis terklasifikasi ke dalam kategori **Stres** dan **Depresi**. Ini menunjukkan bahwa kedua kondisi ini adalah isu kesehatan mental yang paling sering diungkapkan secara online.
2.  **Keterkaitan Sentimen**: Ada tumpang tindih signifikan dalam bahasa yang digunakan untuk menggambarkan **Depresi** dan **Suicidal**. Hal ini menyiratkan perlunya intervensi yang lebih spesifik untuk membedakan kedua kondisi ini.
3.  **Keterbatasan Identifikasi**: Model menunjukkan kesulitan dalam mengklasifikasikan kondisi yang kurang umum seperti **Bipolar** dan **Personality Disorder**, yang mungkin membutuhkan data atau pendekatan yang lebih spesifik.

-----

### **AI Support Explanation**

Proyek ini sepenuhnya didukung oleh **IBM Granite Large Language Models (LLMs)**, yang diakses melalui **Replicate**. Penggunaan AI dalam proyek ini mencakup:

  * **Klasifikasi Teks**: Model Granite digunakan untuk mengategorikan setiap pernyataan ke dalam salah satu dari tujuh status kesehatan mental yang telah ditentukan.
  * **Prompt Engineering**: Daripada melatih model dari awal, kami menggunakan teknik **few-shot prompting** dengan memberikan beberapa contoh dalam *prompt* untuk memandu model melakukan klasifikasi dan ringkasan dengan akurat.
  * **Analisis Data**: AI membantu mempercepat proses analisis data dan memberikan wawasan yang tidak mungkin didapatkan secara manual, seperti mengidentifikasi pola kebahasaan dan sentimen dalam volume data yang besar.

  **Author**: Bondan Tiur Mahendra
  **Email**: bm333936@gmail.com
  **LinkedIn**: [linkedin.com/in/bondantieurmahendra](https://www.linkedin.com/in/bondan-tiur-mahendra/)
