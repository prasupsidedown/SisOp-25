<a name="_hlk191278482"></a>**TUGAS**

**SISTEM OPERASI**

(Rangkuman)


![](Aspose.Words.30dd7e83-bf20-4078-ac66-405a608b4bd5.001.png)


Dosen Pengampu :

Dr Ferry Astika Saputra ST, M.Sc

OLEH :

Muhammad Faris Musyaffa

3124521021

D3 Teknik Informatika A


POLITEKNIK ELEKTRONIKA NEGERI

SURABAYA




**1.	 Layout Memori dalam Sistem Multiprogrammed**

- Memori utama dibagi menjadi beberapa bagian, dengan sistem operasi ditempatkan di bagian atas dan beberapa proses pengguna di bagian bawah.
- Pendekatan ini memungkinkan beberapa proses dapat dieksekusi secara bersamaan, meningkatkan efisiensi penggunaan sumber daya.

**2.	 Mode Dual dan Multimode**

- Sistem operasi menerapkan mode dual untuk melindungi dirinya sendiri dan komponen penting lainnya.
- Terdapat dua mode utama: mode pengguna dan mode kernel, di mana bit mode menentukan mode eksekusi saat ini.
- Instruksi tertentu bersifat *privileged* dan hanya dapat dijalankan dalam mode kernel untuk mencegah akses yang tidak sah.
- Beberapa CPU modern mendukung multi-mode, termasuk *Virtual Machine Manager (VMM)* untuk mendukung eksekusi mesin virtual.

**3.	 Transisi dari Mode Pengguna ke Mode Kernel**

- Timer digunakan untuk memastikan proses tidak berjalan tanpa batas dan tidak menghabiskan sumber daya secara berlebihan.
- Sistem operasi mengatur timer yang akan menginterupsi sistem setelah waktu tertentu.
- Ketika timer mencapai nol, sistem operasi mengambil kembali kendali untuk menjaga kestabilan dan efisiensi sistem.

**4. 	Manajemen Proses**

- Proses adalah program yang sedang dieksekusi, berbeda dengan program pasif yang belum berjalan.
- Untuk menjalankan proses, diperlukan sumber daya seperti CPU, memori, I/O, dan data inisialisasi.
- Setelah proses selesai, sumber daya yang digunakan harus dibebaskan kembali ke sistem.
- Proses *single-threaded* memiliki satu program counter untuk melacak instruksi yang dieksekusi.
- Proses *multi-threaded* memiliki satu program counter per thread, memungkinkan eksekusi secara paralel.
- Sistem sering kali menjalankan banyak proses secara bersamaan dengan memanfaatkan teknik *multiplexing* CPU.

**5. 	Aktivitas Manajemen Proses**

- Sistem operasi bertanggung jawab atas berbagai aktivitas manajemen proses, termasuk:
  - Pembuatan dan penghapusan proses.
  - Penundaan dan kelanjutan proses.
  - Sinkronisasi antar proses.
  - Komunikasi antar proses.
  - Penanganan *deadlock*.






**6. 	Manajemen Memori**

- Semua instruksi dan data dari program yang sedang berjalan harus dimuat dalam memori utama.
- Sistem operasi bertugas mengelola penggunaan memori, menentukan bagian mana yang digunakan oleh proses tertentu.
- Fungsi utama dalam manajemen memori meliputi:
  - Mengatur data yang perlu dimuat atau dipindahkan dari dan ke memori.
  - Mengalokasikan dan membebaskan ruang memori sesuai kebutuhan.

**7. 	Manajemen Sistem File**

- Sistem operasi menyediakan tampilan logis untuk penyimpanan data dalam bentuk file.
- Berbagai media penyimpanan seperti HDD, SSD, dan Tape Drive dikelola melalui sistem file.
- Fungsi utama dalam manajemen file meliputi:
  - Pembuatan dan penghapusan file serta direktori.
  - Kontrol akses terhadap file.
  - Pemetaan file ke penyimpanan sekunder.
  - Pencadangan file untuk keamanan data.

**8. Manajemen Penyimpanan Massal**

- Penyimpanan massal digunakan untuk menyimpan data dalam jumlah besar yang tidak dapat disimpan di memori utama.
- Manajemen penyimpanan sangat penting untuk meningkatkan efisiensi dan kecepatan sistem.
- Beberapa tugas utama sistem operasi dalam manajemen penyimpanan meliputi:
  - *Mounting* dan *unmounting* perangkat penyimpanan.
  - Pengelolaan ruang kosong dalam penyimpanan.
  - Alokasi penyimpanan dan penjadwalan disk.
  - Partisi dan perlindungan data.
- Selain disk utama, sistem operasi juga mengelola penyimpanan tambahan seperti *optical storage* dan *magnetic tape* untuk kebutuhan penyimpanan jangka panjang.
