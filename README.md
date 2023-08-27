Panduan Penggunaan Alat
Rancang Bangun Sistem Penyiraman Pestisida dan Deteksi Hama Menggunakan Metode YOLO
1.	Pasang alat pada area hidroponik sesuai dengan lokasi yang akan digunakan.
2.	Pastikan kamera diposisikan dengan baik agar dapat mengambil gambar dengan optimal.
3.	Sambungkan alat ke sumber listrik 220v untuk memberikan daya yang diperlukan.
4.	Sambungkan alat ke jaringan, seperti Wi-Fi, menggunakan kabel LAN yang sesuai.
5.	Cek IP rasberry dengan software IP Scanner
6.	Jika sudah mendapatkan IP raspberry pi masuk kedalam putty ssh dan masuk kedalam raspberry.
7.	Login User
User	: pi
Password	: raspberry
Ketik “vncserver-virtual”
8.	Jika sudah terhubung ke ssh buka VNC dengan menggunakan IP Raspberry Pi untuk mengakses antarmuka.
9.	Dalam folder, temukan dan buka file "/home/pi/Documents/SKRIPSIYOLO/dikumpulkan fix.py".
10.	Pastikan port kamera yang digunakan cocok dengan pengaturan di dalam script (cv.videocapture()).
11.	Jalankan script yang terdapat dalam file tersebut untuk memulai proses.
12.	Cari dan buka file "/home/pi/Documents/Node Center/Skripsifix.py".
13.	Jalankan script Skripsifix.py untuk menjalankan fungsi pusat alat node center.
14.	Buka browser, buka halaman website"localhost/adminhub-master/index.php".
15.	Periksa apakah semua fungsi sudah berjalan seperti yang diharapkan.
16.	Lakukan penjadwalan penyiraman sesuai dengan kebutuhan, termasuk jam dan hari yang diinginkan.
17.	Setelah semua langkah di atas selesai, alat siap untuk digunakan.

Login Raspberry Pi
User	: Pi
Password	: raspberry
Login PHPMYADMIN
User	: admin
Password	: password

