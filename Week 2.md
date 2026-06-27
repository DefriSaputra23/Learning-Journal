# Week 02 - Manajemen Memori

## 📚 Topik
- Alokasi Memori Dinamis menggunakan `malloc()` pada Bahasa C
- Garbage Collection pada Java

## 📝 Ringkasan Pembelajaran

Pada pertemuan ini saya mempelajari konsep dasar manajemen memori pada pemrograman, khususnya mengenai alokasi memori dinamis menggunakan fungsi `malloc()` pada bahasa C serta mekanisme Garbage Collection pada Java. Saya memahami bahwa `malloc()` memungkinkan program mengalokasikan memori sesuai kebutuhan saat program berjalan sehingga penggunaan memori menjadi lebih fleksibel. Selain itu, saya juga mempelajari bahwa Java memiliki Garbage Collector yang secara otomatis mengelola memori dengan menghapus objek yang sudah tidak digunakan sehingga dapat mengurangi risiko terjadinya *memory leak*.

## ✅ Apa yang Dipahami

Saya memahami bahwa penggunaan `malloc()` memberikan kendali penuh kepada programmer dalam mengelola memori, namun setiap alokasi harus diikuti dengan proses `free()` agar memori tidak terbuang sia-sia. Saya juga memahami bahwa Garbage Collection di Java membantu mengotomatisasi pengelolaan memori sehingga programmer tidak perlu membebaskan memori secara manual. Perbedaan kedua pendekatan ini menunjukkan adanya keseimbangan antara fleksibilitas dan kemudahan dalam pengelolaan memori.

## ❓ Apa yang Masih Membingungkan

Saya masih ingin memahami lebih dalam bagaimana Garbage Collector menentukan objek yang sudah tidak digunakan dan bagaimana proses tersebut memengaruhi performa aplikasi. Selain itu, saya juga ingin mempelajari strategi pengelolaan memori yang digunakan pada bahasa pemrograman lain.

## 📖 Referensi

- https://www.petanikode.com/c-malloc/
- https://www.ibm.com/id-id/think/topics/garbage-collection-java
