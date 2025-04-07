<div align="center">

## TUGAS SISTEM OPERASI

### **RANGKUMAN APPENDIX**

![Pens Logo](https://belalangkecap.it.student.pens.ac.id/logo.png)

---

**Dosen Pengampu:**  
Dr. Ferry Astika Saputra, S.T., M.Sc.

**Disusun Oleh:**  
Muhammad Faris Musyaffa  
3124521021

---

### TEKNIK INFORMATIKA PSDKU LAMONGAN  
DEPARTEMEN TEKNIK INFORMATIKA DAN KOMPUTER  
POLITEKNIK ELEKTRONIKA NEGERI SURABAYA  

</div>

## 1. Migrasi Fitur
Fitur yang awalnya hanya tersedia di komputer besar (mainframe), kini banyak ditemukan di perangkat kecil seperti mikrokomputer dan gadget genggam. Migrasi ini menunjukkan bahwa konsep sistem operasi dapat diterapkan di berbagai platform. Misalnya, sistem MULTICS yang dikembangkan antara 1965–1970 untuk mainframe GE-645, menjadi cikal bakal UNIX yang dibuat untuk minikomputer PDP-11 pada 1970. UNIX kemudian menginspirasi sistem operasi mikrokomputer di era 1980-an. Beberapa fitur tersebut kini digunakan dalam sistem modern seperti Windows, macOS, dan Linux—bahkan pada perangkat sekecil PDA sekalipun.

## 2. Sistem Awal
Sebelum 1940-an, perangkat komputasi dibuat hanya untuk tugas tertentu dan sulit dimodifikasi. Pada era 1940-an, Alan Turing, John von Neumann, dan rekan-rekannya mulai mengembangkan komputer dengan konsep stored program, yang menjadi dasar komputer modern.

Manchester Mark 1 yang berjalan pada 1949 adalah salah satu implementasi awal konsep ini. Ferranti Mark 1 kemudian menjadi komputer komersial pertama pada 1951. Saat itu, komputer dioperasikan langsung melalui konsol oleh programmer, dengan input berupa kartu berlubang, pita kertas, atau panel saklar. Output dipantau dan diuji melalui konsol, lalu dicetak atau diproses lebih lanjut.

## 2.1 Komputer Khusus
Seiring waktu, perangkat keras dan lunak berkembang. Perangkat seperti printer, pembaca kartu, dan pita magnetik mulai digunakan. Program bantu seperti assembler, loader, dan linker muncul untuk memudahkan pemrograman. Subrutin khusus atau device driver dibuat untuk mengelola perangkat I/O tanpa perlu menulis ulang kode.

## 2.2 Sistem Komputer Bersama
Untuk mengurangi waktu yang terbuang, dua solusi diterapkan:
Pertama, pekerjaan operasional komputer dilakukan oleh operator profesional, bukan langsung oleh programmer. Kedua, pekerjaan serupa dikumpulkan dalam kelompok untuk dijalankan secara berurutan, sehingga waktu persiapan lebih efisien.

Meskipun sistem batch ini meningkatkan efisiensi, kendala tetap muncul karena perangkat I/O masih jauh lebih lambat dibandingkan kecepatan CPU. Bahkan perangkat I/O tercepat sekalipun tak mampu mengejar laju pemrosesan CPU, sehingga kesenjangan kecepatan tetap menjadi masalah.

## 2.3 Overlapped I/O
Komputer membaca data dari pita yang telah diisi sebelumnya, sehingga tidak bergantung langsung pada kecepatan perangkat input/output fisik. Solusi ini meningkatkan efisiensi sistem batch secara signifikan.

Selanjutnya, teknologi disk memungkinkan akses data secara acak dan lebih cepat. Konsep spooling pun diperkenalkan, yaitu penggunaan disk sebagai buffer besar untuk menampung data input/output hingga siap diproses.

Misalnya, sistem bisa membaca input untuk satu program, mencetak output dari program lain, dan menjalankan proses ketiga dalam waktu bersamaan. Konsep ini mempercepat seluruh sistem dan membuka jalan bagi multiprogramming, dasar dari sistem operasi modern yang kita gunakan saat ini.

