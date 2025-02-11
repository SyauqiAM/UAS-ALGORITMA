# UAS-ALGO| Sistem Absensi Swimming School
## **Tujuan dari program Java tersebut adalah** untuk mengelola dan mencatat kehadiran siswa di sebuah sekolah renang secara sederhana. Program ini dirancang untuk memudahkan USER (misalnya untuk, guru, pelatih, dan administrator) dalam melakukan beberapa tugas terkait kehadiran siswa
1. Menambahkan Siswa
   - Program memungkinkan user untuk menambahkan nama siswa ke dalam sistem. Setiap siswa yang ditambahkan akan disimpan dalam daftar dan status kehadiran awalnya diatur dengan "Tidak Hadir".

2. Mencatat Kehadiran Siswa
   - user dapat mencatat kehadiran siswa pada hari tertentu. Program akan menampilkan daftar siswa yang terdaftar, dan user dapat memilih siswa yang hadir dengan memasukkan nomor urut siswa tersebut. Status kehadiran siswa yang dipilih akan diubah menjadi "Hadir".

3. Menampilkan Daftar Kehadiran
   - Program dapat menampilkan daftar semua siswa beserta status kehadiran mereka (Hadir atau Tidak Hadir). Ini berguna untuk melihat ringkasan kehadiran siswa pada hari tersebut.

4. Menyimpan Data Sementara
   - Data siswa dan kehadiran disimpan sementara dalam `ArrayList` selama program berjalan. Ini memungkinkan user untuk mengelola data tanpa perlu menggunakan database eksternal.

5. Memudahkan Pengelolaan Kehadiran
   - Program ini dirancang untuk memudahkan pengelolaan kehadiran siswa dalam konteks yang sederhana, seperti di sekolah renang atau kegiatan ekstrakurikuler lainnya. Dengan program ini, user dapat dengan cepat mencatat dan memeriksa kehadiran siswa.

>. Contoh
   Menambahkan Siswa:
     - user memilih opsi 1 dan memasukkan nama siswa, misalnya "Syauqi".
     - Program akan menambahkan "Syauqi" ke dalam daftar siswa.
   Mencatat Kehadiran:
     - user memilih opsi 2, melihat daftar siswa, dan memilih nomor siswa yang hadir, misalnya nomor 1 (Syauqi).
     - Program akan mencatat bahwa Syauqi hadir.
   Menampilkan Kehadiran:
     - user memilih opsi 3, dan program akan menampilkan daftar siswa beserta status kehadiran mereka, misalnya "Syauqi - Hadir atau tidak hadir".

## *Contoh Penggunaan dalam Dunia Nyata:*

- Seorang guru sekolah renang dapat menggunakan program ini untuk mencatat kehadiran siswa setiap hari.
- Administrator dapat menambahkan siswa baru ke dalam sistem saat ada pendaftaran baru.
- Program ini juga dapat digunakan untuk melihat laporan kehadiran harian siswa.
