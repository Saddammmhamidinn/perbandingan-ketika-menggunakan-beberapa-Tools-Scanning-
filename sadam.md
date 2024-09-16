PERBANDINGAN KETIKA MENGGUNAKAN BEBERAPA TOOLS SCANNING :
- NMAP (VIA TERMINAL)
- ZENMAP (VIA APLIKASI)
- ANGRY IP SCAN (VIA APLIKASI)

Nama : M saddam hamidin 
Nim : 090305822246004
Kelas " TK5B


1. Nmap (Via terminal kali linux)
   
![Nmap kali linux](https://github.com/user-attachments/assets/605f40c4-22b2-46aa-b06f-15f12eefa041)

Nmap (Nerwork Mapper) adalah alat pemindaian sumber tebuka untuk eksplorasi jaringan dan keamanan.

Antarmuka : Command-line

Fitur utama : Dapat melakukan pemindaian port, penemuan host, penemuan sistem operasi, sidik jari layanan, serta penemuan firewall dan ids. Mendukung pembuatan skrip melalui Nmap Scripting engine (NSE),
              memungkinkan otomatisasi tugas-tugas tertentu. anda dapat melakukan pemindaian TCP dan UDP, serta pemindaian tersembunyi untuk menghindari deteksi. mendukung berbagai jenis pemindaian seperti
              pemindaian SYN, pemindaian ACK, dan pemindaian FIN.

Kelebihan : - Sangat fleksibel, terutama untuk pengguna yang sudah berpengalaman
            - Mampu bekerja dengan sangat baik dijaringan besar mendukung berbagai kustomisasi.

Kekurangan : - Diperlukan pengetahuan teknis yang cukup untuk menggunakan secara optimal
             - Kurva belajar cukup curam bagi pemula




2. Zenmap (Via Aplikasi)

![Screenshot 2024-09-16 222118](https://github.com/user-attachments/assets/73b3551e-1512-45ab-9c89-311bd3d971ca)


Zenmap adalah versi GUI dari Nmap yang dimaksudkan untuk memudahkan pengguna menggunakan Nmap tanpa harus menguasai baris perintah

Antarmuka : Graphical User Interface (GUI)

Fitur utama : Zenmap sebenarnya hanya berfungsi sebagai frontend untuk Nmap, sehingga memiliki semua fitur Nmap.
              Berbagai profil pemindaian tersedia untuk memudahkan penggunaan pemula. hasil scan ditampilkan dalam 
              visualisasi yang mudah dibaca seperti diagram dan grafik. Mendukung pembuatan dan penyimpanan sesi pemindaian
              untuk analisis selanjutnya.

Kelebihan : Mudah digunakan bahkan bagi pengguna yang belum familiar dengan terminal. Visualisasi yang lebih mudah dan ramah pengguna.
            anda dapat mengekspor hasil scan harian ke berbagai frmat seperti XML, HTML, dll

Kekurangan : Karena ini GUI, maka bisa lebih lambat dibandingkan menjalankan Nmap langsung dari terminal, khususnya pada jaringan besar.
             Tidak sekuat dan selengkap menggunakan Nmap melalui terminal, terutama ketika menggunakan opsi pemindaian yang rumit




3. Angry IP Scan (Via aplikasi)
   
![Screenshot 2024-09-16 223654](https://github.com/user-attachments/assets/271d1b12-f5c9-47e8-95d0-eba74c153d1f)

Angry IP Scan adalah aplikasi pemindaian jaringan yang ringan dan cepat, fokus pada kemudahanan penggunaan dan kecepatan pemindaian

Antarmuka : Graphical User Interface (GUI)

Fitur utama : Pindai alamat ip dalam rentang tertentu dan periksa port yang terbuka, Menampilkan informasi dasar seperti IP, nama host
              dan status port. Hasil scan dapat disimpan dalam berbagai format seperti CSV, TXT, dan XML. plugin yang dapat
              memperluas fungsionalitas pemindaian anda.

Kelebihan : Sangat mudah digunakan bahkan untuk pemula, proses pemindaian cepat cocok untuk jaringan yang keci berjalan lintas
            Platform (Linux, Windows, macOS0. Ukuran aplikasi kecil dan ringan.

Kekurangan : Fungsionalitasnya terbatas di bandingkan Nmap, terutama dalam hal penemuan mendalam (penemuan sistem operasi, layanan, pemindaian kerentanan, DLL.) 
             Tidak cocok untuk memindai jaringan yang besar dan kompleks.

Kesimpulan Perbandingan dari ketiga tersebut :

Berikut perbandingan antara Nmap (via Terminal), Zenmap (via GUI), dan Angry IP Scanner (via GUI). Nmap merupakan tool scanning yang sangat kuat dan fleksibel, ideal untuk pengguna berpengalaman karena menawarkan berbagai opsi scanning dan mendukung scripting, namun membutuhkan pemahaman teknis yang cukup tinggi. Zenmap, versi GUI dari Nmap, lebih mudah digunakan dengan visualisasi yang baik dan profil scanning yang siap pakai, meski sedikit lebih lambat dibandingkan versi terminal. Angry IP Scanner, di sisi lain, adalah tool scanning yang cepat, ringan, dan sangat sederhana, cocok untuk jaringan kecil hingga menengah, tetapi dengan fitur yang terbatas dibandingkan dua tool lainnya, terutama dalam hal deteksi OS dan layanan jaringan. Pemilihan tool bergantung pada kebutuhan pengguna serta skala jaringan yang hendak dipindai.
