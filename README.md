# PRAKTIKUM 1 – PySpark Simple Job  
Proyek: BIGDATA-SPARK-230104040059

Program ini dibuat untuk memenuhi instruksi Praktikum 1 mata kuliah **Big Data Technology**.  
Praktikum ini berfokus pada pengenalan Apache Spark menggunakan PySpark untuk pemrosesan data dasar.

---

## 👩‍🎓 Identitas Mahasiswa
Nama : Siti Magfiratun Warahmah  
NIM  : 230104040059  

---

## 🚀 Deskripsi Program
Program ini merupakan implementasi sederhana Apache Spark menggunakan PySpark.

Spark job yang dibuat bertujuan untuk:

✔ Membuat SparkSession  
✔ Membuat DataFrame dari dataset sederhana  
✔ Melakukan proses agregasi data  
✔ Menampilkan hasil pemrosesan data  

Dataset yang digunakan berupa data kategorikal dengan nilai numerik.

---

## 🛠️ Teknologi yang Digunakan
Lingkungan pengembangan program:

- Python 3.10  
- Apache Spark  
- PySpark  
- Visual Studio Code  

---

## 📊 Dataset
Dataset yang digunakan dalam program:

Category | Value  
A        | 10  
B        | 20  
A        | 30  

Dataset ini digunakan untuk simulasi proses agregasi data pada Spark.

---

## ⚙️ Cara Kerja Program
Program berjalan melalui beberapa tahapan utama:

### 1️⃣ Inisialisasi SparkSession  
SparkSession dibuat sebagai entry point Apache Spark.

### 2️⃣ Pembuatan Dataset  
Dataset sederhana dibuat menggunakan struktur list Python.

### 3️⃣ Pembuatan DataFrame  
Dataset dikonversi menjadi DataFrame PySpark.

### 4️⃣ Proses Agregasi  
DataFrame diproses menggunakan operasi:

groupBy("category").sum("value")

Operasi ini mengelompokkan data berdasarkan kategori dan menjumlahkan nilai.

### 5️⃣ Menampilkan Output  
Hasil agregasi ditampilkan ke terminal.

---

## ✅ Hasil Eksekusi
Output program setelah dijalankan:

+--------+----------+  
|category|sum(value)|  
+--------+----------+  
|A       |40        |  
|B       |20        |  
+--------+----------+  

Hasil menunjukkan bahwa proses agregasi data berhasil dijalankan.

---

## 🎯 Kesimpulan
Praktikum ini menunjukkan bahwa:

✔ SparkSession berhasil dibuat  
✔ DataFrame berhasil diproses  
✔ Operasi agregasi berjalan dengan benar  
✔ Output data ditampilkan tanpa error  

---

## ▶️ Cara Menjalankan Program
Pastikan PySpark telah terinstall:

```bash

pip install pyspark
